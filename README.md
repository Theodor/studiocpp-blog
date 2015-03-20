# studiocpp-blog
For "Studio 12.4 C++11 + Boost" blog entry

Configuration header, describing Studio C++ in C++03 mode:
  * user.hpp

Supporting patches:
  * sunstdlib-removal.patch - getting rid of stlport in toolset=sun config
  * lockpool.patch - fix for libs/atomic Boost bug
  * sentry.patch - workaround for Studio bug
