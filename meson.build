
cxx = meson.get_compiler('cpp')
libSDL2 = cxx.find_library('SDL2')

libImgui = library('imgui', [
  'imgui.cpp',
  'imgui_demo.cpp',
  'imgui_draw.cpp',
  'imgui_tables.cpp',
  'imgui_widgets.cpp',
  'backends/imgui_impl_sdl.cpp',
  'backends/imgui_impl_sdlrenderer.cpp',
  ],
  include_directories: '.',
  dependencies: libSDL2)
