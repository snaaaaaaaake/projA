cmake_minimum_required(VERSION 3.17)

project(projA)

include(FetchContent)


FetchContent_Declare(
  projX
  GIT_REPOSITORY
  https://github.com/snaaaaaaaake/projX.git
  )

FetchContent_MakeAvailable(projX)
