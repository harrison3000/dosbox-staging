libmisc_sources = [
  'cross.cpp',
  'fs_utils_posix.cpp',
  'fs_utils_win32.cpp',
  'messages.cpp',
  'programs.cpp',
  'setup.cpp',
  'soft_limiter.cpp',
  'support.cpp',
]

libmisc = static_library('misc', libmisc_sources,
                         include_directories : incdir,
                         dependencies : sdl2_dep)

libmisc_dep = declare_dependency(link_with : libmisc)

internal_deps += libmisc_dep
