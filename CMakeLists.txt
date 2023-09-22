cmake_minimum_required(VERSION 3.22)

project(
  RFinder 
  VERSION 1.0.0 
  LANGUAGES C CXX
)

set(SERVER_APP_NAME "RFinderServer")
set(CLIENT_CLI_APP_NAME "RFinderClientCLI")
set(NETWORK_LIB_NAME "RFinderNetwork")
set(FS_LIB_NAME "RFinderFS")

add_subdirectory(server)
add_subdirectory(client_cli)
add_subdirectory(network)
add_subdirectory(fs)

