set(CPW_SRC
    cpwgap.cpp
    cpwline.cpp
    cpwopen.cpp
    cpwshort.cpp
    cpwstep.cpp)

add_library(coreCpw OBJECT ${CPW_SRC})
