set(SOURCES
  test.cpp
)

add_executable(paltest_isbadreadptr_test1
  ${SOURCES}
)

add_dependencies(paltest_isbadreadptr_test1 coreclrpal)

target_link_libraries(paltest_isbadreadptr_test1
  ${COMMON_TEST_LIBRARIES}
)
