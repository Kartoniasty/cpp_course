project(TemplateFunctionsAndTypeInterference)

# add the executable
add_executable(TemplateFunctionsAndTypeInterference TemplateFunctionsAndTypeInterference.cpp)
target_compile_options(TemplateFunctionsAndTypeInterference PRIVATE -Wall -Wextra -fdiagnostics-color=always)
