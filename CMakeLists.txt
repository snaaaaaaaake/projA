cmake_minimum_requiredn(VERSION 3.17)

project(projA)

include(FetchContent)


FetchContent_Declare(
  projX
  https://github.com/snaaaaaaaake/projX.git
  )

FetchContent_MakeAvailable(projX)
