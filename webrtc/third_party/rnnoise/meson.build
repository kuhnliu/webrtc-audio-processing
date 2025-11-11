rnnoise_sources = [
  'src/rnn_vad_weights.cc',
]

librnnoise = static_library('rnnoise',
    rnnoise_sources,
    dependencies: common_deps,
    include_directories: webrtc_inc,
    cpp_args : common_cxxflags,
    gnu_symbol_visibility: 'inlineshidden',
    build_by_default: false,
)

rnnoise_dep = declare_dependency(
    link_with: librnnoise
)

