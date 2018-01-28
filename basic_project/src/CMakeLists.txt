# empty for now

INCLUDE_DIRECTORIES( ${CMAKE_CURRENT_SOURCE_DIR})

ADD_LIBRARY( adorable OBJECT adorable.cpp )

ADD_EXECUTABLE( hi hello.cpp )


# Needed only to link missing libraries to the executable (target name)
#TARGET_LINK_LIBRARIES( hi )

