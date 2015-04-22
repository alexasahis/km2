
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 1
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@:)
ECHO = $(ECHO1:0=@echo)

#### Start of system configuration section. ####

srcdir = .
topdir = /opt/rh/ruby200/root/usr/include
hdrdir = /opt/rh/ruby200/root/usr/include
arch_hdrdir = /opt/rh/ruby200/root/usr/include
PATH_SEPARATOR = :
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
prefix = $(DESTDIR)/opt/rh/ruby200/root/usr
rubysitearchprefix = $(sitearchlibdir)/$(RUBY_BASE_NAME)
rubyarchprefix = $(libdir)/$(RUBY_BASE_NAME)
rubylibprefix = $(exec_prefix)/share/$(RUBY_BASE_NAME)
exec_prefix = $(prefix)
vendorarchhdrdir = $(vendorhdrdir)/$(arch)
sitearchhdrdir = $(sitehdrdir)/$(arch)
rubyarchhdrdir = $(DESTDIR)/opt/rh/ruby200/root/usr/include
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(DESTDIR)/opt/rh/ruby200/root/usr/include
rubygemsdir = $(DESTDIR)/opt/rh/ruby200/root/usr/share/rubygems
vendorarchdir = $(DESTDIR)/opt/rh/ruby200/root/usr/lib64/ruby/vendor_ruby
vendorlibdir = $(vendordir)/$(ruby_version)
vendordir = $(DESTDIR)/opt/rh/ruby200/root/usr/share/ruby/vendor_ruby
sitearchdir = $(DESTDIR)./.gem.20150421-213003-147bvzd
sitelibdir = $(DESTDIR)./.gem.20150421-213003-147bvzd
sitedir = $(DESTDIR)/opt/rh/ruby200/root/usr/local/share/ruby/site_ruby
rubyarchdir = $(rubyarchprefix)/$(ruby_version)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitearchincludedir = $(includedir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archlibdir = $(libdir)/$(arch)
ridir = $(datarootdir)/$(RI_BASE_NAME)
mandir = $(DESTDIR)/opt/rh/ruby200/root/usr/share/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib64
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(DESTDIR)/opt/rh/ruby200/root/usr/share/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = $(DESTDIR)/usr/include
includedir = $(DESTDIR)/opt/rh/ruby200/root/usr/include
localstatedir = $(DESTDIR)/opt/rh/ruby200/root/var
sharedstatedir = $(DESTDIR)/opt/rh/ruby200/root/usr/com
sysconfdir = $(DESTDIR)/opt/rh/ruby200/root/etc
datadir = $(DESTDIR)/opt/rh/ruby200/root/usr/share
datarootdir = $(prefix)/share
libexecdir = $(DESTDIR)/opt/rh/ruby200/root/usr/libexec
sbindir = $(DESTDIR)/opt/rh/ruby200/root/usr/sbin
bindir = $(exec_prefix)/bin
archdir = $(rubyarchdir)


CC = gcc
CXX = g++
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -l$(RUBY_SO_NAME)-static
empty =
OUTFLAG = -o $(empty)
COUTFLAG = -o $(empty)

RUBY_EXTCONF_H = extconf.h
cflags   =  $(optflags) $(debugflags) $(warnflags)
optflags = -O3 -fno-fast-math
debugflags = -ggdb3
warnflags = 
CCDLFLAGS = -fPIC
CFLAGS   = $(CCDLFLAGS) -O2 -g -pipe -Wall -Wp,-D_FORTIFY_SOURCE=2 -fexceptions -fstack-protector --param=ssp-buffer-size=4 -mtune=generic -fPIC -I/usr/lib64/libffi-3.0.5/include $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS = -DRUBY_EXTCONF_H=\"$(RUBY_EXTCONF_H)\"  $(DEFS) $(cppflags)
CXXFLAGS = $(CCDLFLAGS) -O2 -g -pipe -Wall -Wp,-D_FORTIFY_SOURCE=2 -fexceptions -fstack-protector --param=ssp-buffer-size=4 -mtune=generic $(ARCH_FLAG)
ldflags  = -L. -fstack-protector -rdynamic -Wl,-export-dynamic 
dldflags =  
ARCH_FLAG = -m64
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = $(CC) -shared
LDSHAREDXX = $(CXX) -shared
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = ruby
RUBY_SO_NAME = ruby
RUBYW_INSTALL_NAME = 
RUBY_VERSION_NAME = $(RUBY_BASE_NAME)-$(ruby_version)
RUBYW_BASE_NAME = rubyw
RUBY_BASE_NAME = ruby

arch = x86_64-linux
sitearch = $(arch)
ruby_version = 
ruby = $(bindir)/ruby
RUBY = $(ruby)
ruby_headers = $(hdrdir)/ruby.h $(hdrdir)/ruby/defines.h $(arch_hdrdir)/ruby/config.h $(RUBY_EXTCONF_H)

RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = rmdir --ignore-fail-on-non-empty -p
MAKEDIRS = /bin/mkdir -p
INSTALL = /usr/bin/install -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp
TOUCH = exit >

#### End of system configuration section. ####

preload = 

libpath = . $(libdir)
LIBPATH =  -L. -L$(libdir)
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = 
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED) -lffi  -lffi -lpthread -lrt -ldl -lcrypt -lm   -lc
ORIG_SRCS = StructByReference.c Call.c LastError.c StructByValue.c ArrayType.c MethodHandle.c Thread.c Variadic.c MemoryPointer.c FunctionInfo.c Types.c LongDouble.c ClosurePool.c DynamicLibrary.c ffi.c Function.c AbstractMemory.c DataConverter.c Pointer.c Struct.c Type.c Buffer.c MappedType.c StructLayout.c Platform.c
SRCS = $(ORIG_SRCS) 
OBJS = StructByReference.o Call.o LastError.o StructByValue.o ArrayType.o MethodHandle.o Thread.o Variadic.o MemoryPointer.o FunctionInfo.o Types.o LongDouble.o ClosurePool.o DynamicLibrary.o ffi.o Function.o AbstractMemory.o DataConverter.o Pointer.o Struct.o Type.o Buffer.o MappedType.o StructLayout.o Platform.o
HDRS = $(srcdir)/ArrayType.h $(srcdir)/rbffi_endian.h $(srcdir)/Platform.h $(srcdir)/Thread.h $(srcdir)/Types.h $(srcdir)/rbffi.h $(srcdir)/LastError.h $(srcdir)/StructByValue.h $(srcdir)/MappedType.h $(srcdir)/LongDouble.h $(srcdir)/Function.h $(srcdir)/MemoryPointer.h $(srcdir)/ClosurePool.h $(srcdir)/Pointer.h $(srcdir)/Struct.h $(srcdir)/AbstractMemory.h $(srcdir)/Call.h $(srcdir)/extconf.h $(srcdir)/StructByReference.h $(srcdir)/DynamicLibrary.h $(srcdir)/Type.h $(srcdir)/MethodHandle.h $(srcdir)/compat.h
TARGET = ffi_c
TARGET_NAME = ffi_c
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).so
EXTSTATIC = 
STATIC_LIB = 

BINDIR        = $(bindir)
RUBYCOMMONDIR = $(sitedir)$(target_prefix)
RUBYLIBDIR    = $(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(sitearchdir)$(target_prefix)
HDRDIR        = $(rubyhdrdir)/ruby$(target_prefix)
ARCHHDRDIR    = $(rubyhdrdir)/$(arch)/ruby$(target_prefix)

TARGET_SO     = $(DLLIB)
CLEANLIBS     = $(TARGET).so 
CLEANOBJS     = *.o  *.bak

all:    $(DLLIB)
static: $(STATIC_LIB)
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS) 2> /dev/null || true

realclean: distclean
install: install-so install-rb

install-so: $(DLLIB) ./.RUBYARCHDIR.time
	$(INSTALL_PROG) $(DLLIB) $(RUBYARCHDIR)
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb install-rb-default
install-rb-default: pre-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
pre-install-rb-default:
	$(ECHO) installing default ffi_c libraries
./.RUBYARCHDIR.time:
	$(Q) $(MAKEDIRS) $(RUBYARCHDIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .C .o

.cc.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.mm.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cxx.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cpp.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.C.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.c.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $<

.m.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $<

$(DLLIB): $(OBJS) Makefile
	$(ECHO) linking shared-object $(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)



$(OBJS): $(HDRS) $(ruby_headers)
