# STB_Image_static_library
STB_Image MSVC project intended for static library compilation

# Why?
When using stb_image.h in Debug mode it's painfully slow, so by compiling it into a static library you can use Release version in Debug builds which massively speeds up for example OpenGL game load times
