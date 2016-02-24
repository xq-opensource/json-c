project(json-c c)

add_library(json-c STATIC
  arraylist.c
  debug.c
  json_c_version.c
  json_object.c
  json_object_iterator.c
  json_tokener.c
  json_util.c
  linkhash.c
  printbuf.c
	random_seed.c
)
