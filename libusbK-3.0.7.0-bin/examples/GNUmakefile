# MinGW64 tdm-gcc (multi-lib) SOLUTION makefile for examples.
#
# !! IMPORTANT: !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# !! Requires multilib GCC
# !! Get it here: http://tdm-gcc.tdragon.net/
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

#
# Copyright (c) 2011-2012 Travis Robinson <libusbdotnet@gmail.com>
# All rights reserved.
#
# Redistribution and use in source and binary forms, with or without
# modification, are permitted provided that the following conditions are met:
# 
#     * Redistributions of source code must retain the above copyright
#       notice, this list of conditions and the following disclaimer.
# 	  
# THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS 
# IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED 
# TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A 
# PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL TRAVIS LEE ROBINSON 
# BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
# CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
# SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
# INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
# CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
# ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF 
# THE POSSIBILITY OF SUCH DAMAGE. 
#

# Commands uses in this makefile:
# (- prefix means ignore errors)
#
MAKE	= make
RM		= -rm -fr

$(info [K] Running examples SOLUTION makefile..)

# make all examples for the specified "arch" (default is x86)
#
.PHONY: all
all: hot-plug-monitor
all: load-driver-api
all: show-device
all: open-device
all: config-interface
all: pipe-policy-timeout
all: xfer-sync
all: xfer-async
all: xfer-stream
all: xfer-iso
all: xfer-async-loop
all: power-policy-suspend
all: pipe-policy-other
all: xfer-iso-read
all: xfer-control
all: enum_descriptors
all: xfer-stream-loop
all: xfer-control-loop

# make the hot-plug-monitor example for the specified "arch" (default is x86)
#
.PHONY: hot-plug-monitor
hot-plug-monitor:
	$(MAKE) --no-print-directory --directory=./hot-plug-monitor $(subst w -- ,,$(MAKEFLAGS)) all
# make the load-driver-api example for the specified "arch" (default is x86)
#
.PHONY: load-driver-api
load-driver-api:
	$(MAKE) --no-print-directory --directory=./load-driver-api $(subst w -- ,,$(MAKEFLAGS)) all
# make the show-device example for the specified "arch" (default is x86)
#
.PHONY: show-device
show-device:
	$(MAKE) --no-print-directory --directory=./show-device $(subst w -- ,,$(MAKEFLAGS)) all
# make the open-device example for the specified "arch" (default is x86)
#
.PHONY: open-device
open-device:
	$(MAKE) --no-print-directory --directory=./open-device $(subst w -- ,,$(MAKEFLAGS)) all
# make the config-interface example for the specified "arch" (default is x86)
#
.PHONY: config-interface
config-interface:
	$(MAKE) --no-print-directory --directory=./config-interface $(subst w -- ,,$(MAKEFLAGS)) all
# make the pipe-policy-timeout example for the specified "arch" (default is x86)
#
.PHONY: pipe-policy-timeout
pipe-policy-timeout:
	$(MAKE) --no-print-directory --directory=./pipe-policy-timeout $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-sync example for the specified "arch" (default is x86)
#
.PHONY: xfer-sync
xfer-sync:
	$(MAKE) --no-print-directory --directory=./xfer-sync $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-async example for the specified "arch" (default is x86)
#
.PHONY: xfer-async
xfer-async:
	$(MAKE) --no-print-directory --directory=./xfer-async $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-stream example for the specified "arch" (default is x86)
#
.PHONY: xfer-stream
xfer-stream:
	$(MAKE) --no-print-directory --directory=./xfer-stream $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-iso example for the specified "arch" (default is x86)
#
.PHONY: xfer-iso
xfer-iso:
	$(MAKE) --no-print-directory --directory=./xfer-iso $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-async-loop example for the specified "arch" (default is x86)
#
.PHONY: xfer-async-loop
xfer-async-loop:
	$(MAKE) --no-print-directory --directory=./xfer-async-loop $(subst w -- ,,$(MAKEFLAGS)) all
# make the power-policy-suspend example for the specified "arch" (default is x86)
#
.PHONY: power-policy-suspend
power-policy-suspend:
	$(MAKE) --no-print-directory --directory=./power-policy-suspend $(subst w -- ,,$(MAKEFLAGS)) all
# make the pipe-policy-other example for the specified "arch" (default is x86)
#
.PHONY: pipe-policy-other
pipe-policy-other:
	$(MAKE) --no-print-directory --directory=./pipe-policy-other $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-iso-read example for the specified "arch" (default is x86)
#
.PHONY: xfer-iso-read
xfer-iso-read:
	$(MAKE) --no-print-directory --directory=./xfer-iso-read $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-control example for the specified "arch" (default is x86)
#
.PHONY: xfer-control
xfer-control:
	$(MAKE) --no-print-directory --directory=./xfer-control $(subst w -- ,,$(MAKEFLAGS)) all
# make the enum_descriptors example for the specified "arch" (default is x86)
#
.PHONY: enum_descriptors
enum_descriptors:
	$(MAKE) --no-print-directory --directory=./enum_descriptors $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-stream-loop example for the specified "arch" (default is x86)
#
.PHONY: xfer-stream-loop
xfer-stream-loop:
	$(MAKE) --no-print-directory --directory=./xfer-stream-loop $(subst w -- ,,$(MAKEFLAGS)) all
# make the xfer-control-loop example for the specified "arch" (default is x86)
#
.PHONY: xfer-control-loop
xfer-control-loop:
	$(MAKE) --no-print-directory --directory=./xfer-control-loop $(subst w -- ,,$(MAKEFLAGS)) all

# make all examples for x86 and amd64 archs. ("arch" argument not used)
#
.PHONY: multi-all
multi-all: 
	$(MAKE) $(MAKEFLAGS) arch=x86 all
	$(MAKE) $(MAKEFLAGS) arch=amd64 all

# reamove all temporary/output files and directories
#
.PHONY: clean
clean:
	$(MAKE) --directory=./hot-plug-monitor $(MAKEFLAGS) clean
	$(MAKE) --directory=./load-driver-api $(MAKEFLAGS) clean
	$(MAKE) --directory=./show-device $(MAKEFLAGS) clean
	$(MAKE) --directory=./open-device $(MAKEFLAGS) clean
	$(MAKE) --directory=./config-interface $(MAKEFLAGS) clean
	$(MAKE) --directory=./pipe-policy-timeout $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-sync $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-async $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-stream $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-iso $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-async-loop $(MAKEFLAGS) clean
	$(MAKE) --directory=./power-policy-suspend $(MAKEFLAGS) clean
	$(MAKE) --directory=./pipe-policy-other $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-iso-read $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-control $(MAKEFLAGS) clean
	$(MAKE) --directory=./enum_descriptors $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-stream-loop $(MAKEFLAGS) clean
	$(MAKE) --directory=./xfer-control-loop $(MAKEFLAGS) clean
	$(RM) ./_ReSharper*
