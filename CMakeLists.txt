cmake_minimum_required(VERSION 2.6.0)

# here we specify that the project is C language only, so the default
# C compiler on the system will be used
project(myprogram C)

add_executable(server server.c)
add_executable(client client.c)
add_executable(server2 server2.c)
add_executable(client2 client2.c)
add_executable(get_ip get_ip.c)
