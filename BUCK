load('//:buckaroo_macros.bzl', 'buckaroo_cell')

glfw = buckaroo_cell('github.com/buckaroo-pm/glfw')

deps = [
  glfw + '//:glfw',
  glfw + '//deps:glad',
  glfw + '//deps:linmath',
]

cxx_binary(
  name = 'boing',
  srcs = [
    'boing.c',
  ],
  deps = deps,
)
