include_directories(../../include)
set(tutorial j1j2)
add_executable(${tutorial} ${tutorial}.cc)
target_link_libraries(${tutorial} utility itensor matrix)
