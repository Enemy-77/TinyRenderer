
file(GLOB_RECURSE HEADER_FILES *.h)
file(GLOB_RECURSE SOURCE_FILES *.cc)

source_group_by_dir(HEADER_FILES)
source_group_by_dir(SOURCE_FILES)

add_executable(TinyRenderer main.cc)