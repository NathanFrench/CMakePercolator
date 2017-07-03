if (NOT EXISTS ${PROJECT_SOURCE_DIR}/thirdparty.cmake)
    message(FATAL_ERROR 
        "RUN THIS FIRST:\ncd ${PROJECT_SOURCE_DIR}\n./bootstrap.sh\ncd ${PROJECT_BINARY_DIR}") 
endif()

include (${PROJECT_SOURCE_DIR}/thirdparty.cmake)
