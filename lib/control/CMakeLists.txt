set(CONTROL_HEADERS
    control/control.h
    control/control-commands.h
    control/control-main.h
    control/control-server.h
    PARENT_SCOPE)

set(CONTROL_SOURCES
    control/control.c
    control/control-commands.c
    control/control-main.c
    control/control-server.c
    control/control-server-unix.c
    PARENT_SCOPE)

add_test_subdirectory(tests)
