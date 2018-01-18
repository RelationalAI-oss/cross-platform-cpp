if(CMAKE_SOURCE_DIR STREQUAL CMAKE_CURRENT_SOURCE_DIR)

cmake_minimum_required( VERSION 2.8.12 )

	project( cross_platform_cpp )

	enable_testing()
endif()

file(GLOB CROSSPLATFORM_UTF8_HEADERS
        "utf8/*.h"
        )


file(GLOB CROSSPLATFORM_UTF8_SOURCE
        "utf8/*.cpp"
        )

file(GLOB CROSSPLATFORM_UTF8_SRC
        ${CROSSPLATFORM_UTF8_HEADERS}
        ${CROSSPLATFORM_UTF8_SOURCE}
        )

# end of file
