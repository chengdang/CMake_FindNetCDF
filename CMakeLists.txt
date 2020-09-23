cmake_minimum_required(VERSION 3.10)

# set the project name
project(FindNetCDF)
list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_LIST_DIR}/modules")
include(FindNetCDF_A)
message("NETCDF_INCLUDES: ${NETCDF_INCLUDES}")
message("NETCDF_LIBRARIES: ${NETCDF_LIBRARIES}")

include(FindNetCDF_B)
message("netCDF_FOUND: ${netCDF_FOUND}")
message("netCDF_INCLUDE_DIR: ${netCDF_INCLUDE_DIR}")
message("NetCDF_LIBRARIES: ${netCDF_LIBRARIES}")
message("NetCDF_VERSION: ${NetCDFVersion}")
