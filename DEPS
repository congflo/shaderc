use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '5be22f98733c674d532598454ae729253bc53e82',
  'effcee_revision' : '19b4aa87af25cb4ee779a071409732f34bfc305c',
  'glslang_revision': '7fa0731a803e8c02347756df41e0b606a4a34e2d',
  'googletest_revision': '518387203b573f35477fa6872dd54620e70d2bdb',
  're2_revision': '601d9ea3e6a768cb666e71012f0baf812a2d48da',
  'spirv_headers_revision': '88bc5e321c2839707df8b1ab534e243e00744177',
  'spirv_tools_revision': '01e851be93a4be2d91194ed6ec8626038aae5bfb',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
