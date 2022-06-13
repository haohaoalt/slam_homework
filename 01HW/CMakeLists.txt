cmake_minimum_required(VERSION 2.8) #最低版本要求，低了报错
project(homework01)   #项目名称

find_package(OpenCV REQUIRED)  #添加opencv库

include_directories(${OpenCV_INCLUDE_DIRS}) #添加opencv头文件

add_executable(${PROJECT_NAME} rename.cpp) #添加可执行程序，红色标记字体的写法是宏,代表可执行程序的名字,第二个参数是源代码文件
target_link_libraries(${PROJECT_NAME} ${OpenCV_LIBS}) #将库文件链接到可执行程序上