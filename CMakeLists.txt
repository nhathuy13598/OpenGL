cmake_minimum_required(VERSION 3.16)
project(LearnOpenGL)

add_executable(${PROJECT_NAME} src/Application.cpp)

# Use GLFW
find_package(glfw3 REQUIRED)
target_link_libraries(${PROJECT_NAME} glfw)

# Use OpenGL
find_package(OpenGL REQUIRED)
target_link_libraries(${PROJECT_NAME} OpenGL::GL)

# Use Glew
find_package(GLEW REQUIRED)
target_link_libraries(${PROJECT_NAME} GLEW::GLEW)