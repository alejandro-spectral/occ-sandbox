cmake_minimum_required(VERSION 3.10)
project(occ-sandbox)
add_executable(occ-sandbox Main.cpp)
target_include_directories(occ-sandbox PRIVATE /usr/include/opencascade)
target_link_libraries(occ-sandbox PRIVATE 
    TKernel
    TKMath
    TKG2d
    TKG3d
    TKGeomBase
    TKGeomAlgo
    TKBRep
    TKTopAlgo
    TKPrim
    TKShHealing
    TKSTEP
    TKSTEPAttr
    TKSTEP209
    TKXSBase
    TKIGES
    TKBO
)