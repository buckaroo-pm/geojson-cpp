load('//:buckaroo_macros.bzl', 'buckaroo_deps')

cxx_library(
  name = 'geojson-cpp', 
  header_namespace = 'mapbox', 
  exported_headers = subdir_glob([
    ('include/mapbox', '**/*.hpp'), 
  ]), 
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = buckaroo_deps(), 
  visibility = [
    'PUBLIC', 
  ], 
)