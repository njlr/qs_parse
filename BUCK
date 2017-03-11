cxx_library(
  name = 'qs-parse',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 'qs_parse.h'),
  ]),
  srcs = [
    'qs_parse.c',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'example',
  srcs = [
    'qs_example.c',
  ],
  deps = [
    ':qs-parse',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'qs_test.c',
  ],
  deps = [
    ':qs-parse',
  ],
)
