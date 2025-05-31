# glad (GL)

This is a minimal GL loader of [glad](https://github.com/Dav1dde/glad).

## Usage

Using `FetchContent`:
```cmake
include(FetchContent)

FetchContent_Declare(
  glad
  GIT_REPOSITORY https://github.com/yourusername/glad.git
  GIT_TAG        main
)

FetchContent_MakeAvailable(glad)

target_link_libraries(your_target PRIVATE glad::glad)
```
