cmake_minimum_required (VERSION 3.8)

project ("Task_34_5_1")
set(CMAKE_CXX_STANDARD 14)

set (CMAKE_PREFIX_PATH "C:\\Qt\\Qt5.13.0\\5.13.0\\mingw73_64\\lib\\cmake")



find_package(Qt5 COMPONENTS
        Core
        Gui
        Widgets
        REQUIRED)

# Добавьте источник в исполняемый файл этого проекта.
add_executable (Task_34_5_1 "Task_34_5_1.cpp" "Task_34_5_1.h")


target_link_libraries(Task_34_5_1
        Qt5::Core
        Qt5::Gui
        Qt5::Widgets
        )

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
