set(MICROSTRIP_SRC
    mscorner.cpp
    mscoupled.cpp
    mscross.cpp
    msgap.cpp
    mslange.cpp
    msline.cpp
    msmbend.cpp
    msopen.cpp
    msrstub.cpp
    msstep.cpp
    mstee.cpp
    msvia.cpp)

add_library(coreMicrostrip OBJECT ${MICROSTRIP_SRC})
