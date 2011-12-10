PROGS = simple

# Super simple
simple_SRCS = simple.c

# Needs to be after attributes and before custom targets
auto_mk_path ?= $(if $(PROJECT),$(PROJECT)/auto.mk,.)
include $(auto_mk_path)/auto.mk
