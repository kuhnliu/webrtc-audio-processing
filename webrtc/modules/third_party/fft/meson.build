fft_sources = ['fft.c']

libfft = static_library('fft',
    fft_sources,
    dependencies: common_deps,
    include_directories: webrtc_inc,
    c_args: common_cflags,
    cpp_args : common_cxxflags,
    gnu_symbol_visibility: 'inlineshidden',
    build_by_default: false,
)

fft_dep = declare_dependency(
    link_with: libfft
)

