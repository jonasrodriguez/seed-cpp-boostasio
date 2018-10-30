# configure demo
set(DEMO demo)

file(GLOB DEMO_SRC "${DEMO}/main.cpp")

add_executable(demo ${DEMO_SRC})