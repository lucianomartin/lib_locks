# This Makefile is just for modules that compile to static libraries.
# The following include will handle everything, picking up the
# settings in module_build_info
#
#    make all    - will build the library
#    make export - will build the library and export a binary version
#                  of the module into the export/ directory

LOCKS_AS_LIBRARY = 1
XCC_FLAGS = -O2 -report

XMOS_MAKE_PATH ?= ..
include $(XMOS_MAKE_PATH)/xcommon/module_xcommon/build/Makefile.libraries
