cmkae_minimum_required(VERSION 3.20.1)
project(make_projet)

include_directories(MAN.H)

set(SOURCES src/HANGMANM.C
	    SRC/main.c)

add_executable(main
		${SOURCES})