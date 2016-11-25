**Configure**

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ ls
aclocal.m4  bin        configure     erl-build-tool-vars.sh  HOWTO  LICENSE.txt  Makefile.in  otp_client_build.temp_stderr.19090  OTP_VERSION         plt             proposed_updates.json  system       xcomp
AUTHORS     bootstrap  configure.in  erts                    lib    make         otp_build    otp_patch_apply                     otp_versions.table  prebuilt.files  README.md              TAR.include
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ ./configure
Ignoring the --cache-file argument since it can cause the system to be erroneously configured
Disabling caching
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking for g++... g++
checking whether we are using the GNU C++ compiler... yes
checking whether g++ accepts -g... yes
checking for ld... ld
checking for env... /usr/bin/env
checking for GNU make... yes (make)
checking for a BSD-compatible install... /usr/bin/install -c
checking whether ln -s works... yes
checking for ranlib... ranlib
checking ERTS version... 8.1
checking OTP release... 19
checking OTP version... 19.1
configure: creating ./config.status
config.status: creating Makefile
config.status: creating make/output.mk
config.status: creating make/emd2exml
configure: configuring in lib
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/configure' --prefix=/usr/local  --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib
configure: creating ./config.status
configure: configuring in snmp/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for perl... perl
configure: creating ./config.status
config.status: creating mibs/Makefile
configure: configuring in common_test/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
configure: creating ./config.status
config.status: creating priv/x86_64-unknown-linux-gnu/Makefile
configure: configuring in erl_interface/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking how to run the C preprocessor... gcc -E
checking for ranlib... ranlib
checking for ld.sh... no
checking for ld... ld
checking for egrep... grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking for short... yes
checking size of short... 2
checking for int... yes
checking size of int... 4
checking for long... yes
checking size of long... 8
checking for void *... yes
checking size of void *... 8
checking for long long... yes
checking size of long long... 8
checking for ar... ar
checking for a BSD-compatible install... /usr/bin/install -c
checking how to create a directory including parents... /usr/bin/install -c -d
checking for gethostbyname in -lnsl... yes
checking for getpeername in -lsocket... no
checking for ANSI C header files... (cached) yes
checking for sys/wait.h that is POSIX.1 compatible... yes
checking arpa/inet.h usability... yes
checking arpa/inet.h presence... yes
checking for arpa/inet.h... yes
checking fcntl.h usability... yes
checking fcntl.h presence... yes
checking for fcntl.h... yes
checking limits.h usability... yes
checking limits.h presence... yes
checking for limits.h... yes
checking malloc.h usability... yes
checking malloc.h presence... yes
checking for malloc.h... yes
checking netdb.h usability... yes
checking netdb.h presence... yes
checking for netdb.h... yes
checking netinet/in.h usability... yes
checking netinet/in.h presence... yes
checking for netinet/in.h... yes
checking stddef.h usability... yes
checking stddef.h presence... yes
checking for stddef.h... yes
checking for stdlib.h... (cached) yes
checking for string.h... (cached) yes
checking sys/param.h usability... yes
checking sys/param.h presence... yes
checking for sys/param.h... yes
checking sys/socket.h usability... yes
checking sys/socket.h presence... yes
checking for sys/socket.h... yes
checking sys/select.h usability... yes
checking sys/select.h presence... yes
checking for sys/select.h... yes
checking sys/time.h usability... yes
checking sys/time.h presence... yes
checking for sys/time.h... yes
checking for unistd.h... (cached) yes
checking for sys/types.h... (cached) yes
checking for uid_t in sys/types.h... yes
checking for pid_t... yes
checking for size_t... yes
checking whether time.h and sys/time.h may both be included... yes
checking for socklen_t usability... yes
checking for working alloca.h... yes
checking for alloca... yes
checking whether gcc needs -traditional... no
checking for working memcmp... yes
checking for dup2... yes
checking for gethostbyaddr... yes
checking for gethostbyname... yes
checking for gethostbyaddr_r... yes
checking for gethostbyname_r... yes
checking for gethostname... yes
checking for writev... yes
checking for gethrtime... no
checking for gettimeofday... yes
checking for inet_ntoa... yes
checking for memchr... yes
checking for memmove... yes
checking for memset... yes
checking for select... yes
checking for socket... yes
checking for strchr... yes
checking for strerror... yes
checking for strrchr... yes
checking for strstr... yes
checking for uname... yes
checking for res_gethostbyname... no
checking for res_gethostbyname in -lresolv... yes
checking for clock_gettime... yes
checking for mixed cygwin or msys and native VC++ environment... no
checking for mixed cygwin and native MinGW environment... no
checking if we mix cygwin with any native compiler... no
checking if we mix msys with another native compiler... no
checking for native win32 threads... no
checking for pthread_create in -lpthread... yes
checking for getconf... getconf
checking for Native POSIX Thread Library... yes
checking nptl/pthread.h usability... no
checking nptl/pthread.h presence... no
checking for nptl/pthread.h... no
checking pthread.h usability... yes
checking pthread.h presence... yes
checking for pthread.h... yes
checking pthread/mit/pthread.h usability... no
checking pthread/mit/pthread.h presence... no
checking for pthread/mit/pthread.h... no
checking if we can add -Werror=return-type to WERRORFLAGS (via CFLAGS)... yes
configure: creating ./config.status
config.status: creating src/x86_64-unknown-linux-gnu/Makefile
config.status: creating src/x86_64-unknown-linux-gnu/eidefs.mk
config.status: creating src/x86_64-unknown-linux-gnu/config.h
configure: configuring in gs/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for prebuilt tcl/tk in tcl/binaries/x86_64_linux-gnu.tar.gz... not found
configure: creating ./config.status
config.status: creating tcl/x86_64-unknown-linux-gnu/Makefile
config.status: creating tcl/win32/Makefile
configure: configuring in megaco/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking for flex... no
checking for lex... no
checking for yywrap in -lfl... no
checking for yywrap in -ll... no
checking if we can add -Werror=return-type to CFLAGS (via CFLAGS)... yes
checking for usable Dynamic Erlang Driver configuration... yes
checking for perl... perl
configure: creating ./config.status
config.status: creating examples/meas/Makefile
configure: creating ./config.status
config.status: creating examples/meas/Makefile
config.status: creating src/flex/x86_64-unknown-linux-gnu/Makefile
configure: configuring in odbc/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/odbc/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/odbc/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking for mixed cygwin or msys and native VC++ environment... no
checking for mixed cygwin and native MinGW environment... no
checking if we mix cygwin with any native compiler... no
checking if we mix msys with another native compiler... no
checking whether make sets $(MAKE)... yes
checking for ld.sh... no
checking for ld... ld
checking for rm... /bin/rm
checking for connect... yes
checking for gethostbyname... yes
checking how to run the C preprocessor... gcc -E
checking for egrep... grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking fcntl.h usability... yes
checking fcntl.h presence... yes
checking for fcntl.h... yes
checking netdb.h usability... yes
checking netdb.h presence... yes
checking for netdb.h... yes
checking for stdlib.h... (cached) yes
checking for string.h... (cached) yes
checking sys/socket.h usability... yes
checking sys/socket.h presence... yes
checking for sys/socket.h... yes
checking winsock2.h usability... no
checking winsock2.h presence... no
checking for winsock2.h... no
checking windows.h usability... no
checking windows.h presence... no
checking for windows.h... no
checking for sql.h... no
checking for sqlext.h... no
checking for an ANSI C-conforming const... yes
checking for size_t... yes
checking for struct sockaddr_in6.sin6_addr... yes
checking for memset... yes
checking for socket... yes
checking for native win32 threads... no
checking for pthread_create in -lpthread... yes
checking for getconf... getconf
checking for Native POSIX Thread Library... yes
checking nptl/pthread.h usability... no
checking nptl/pthread.h presence... no
checking for nptl/pthread.h... no
checking pthread.h usability... yes
checking pthread.h presence... yes
checking for pthread.h... yes
checking pthread/mit/pthread.h usability... no
checking pthread/mit/pthread.h presence... no
checking for pthread/mit/pthread.h... no
checking for void *... yes
checking size of void *... 8
checking for odbc in standard locations... no
configure: WARNING: No odbc library found skipping odbc
configure: WARNING: "ODBC library - header check failed"
configure: WARNING: "ODBC library - link check failed"
checking if we can add -Werror=return-type to CFLAGS (via CFLAGS)... yes
configure: creating ./config.status
config.status: creating c_src/x86_64-unknown-linux-gnu/Makefile
configure: configuring in wx/.
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/./configure' --prefix=/usr/local  '--prefix=/usr/local' '--cache-file=/dev/null' '--srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib' --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/.
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking for g++... g++
checking whether we are using the GNU C++ compiler... yes
checking whether g++ accepts -g... yes
checking for ranlib... ranlib
checking how to run the C preprocessor... gcc -E
configure: Building for linux-gnu
checking for mixed cygwin or msys and native VC++ environment... no
checking for mixed cygwin and native MinGW environment... no
checking if we mix cygwin with any native compiler... no
checking if we mix msys with another native compiler... no
checking for egrep... grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking for void *... yes
checking size of void *... 8
checking GL/gl.h usability... no
checking GL/gl.h presence... no
checking for GL/gl.h... no
checking OpenGL/gl.h usability... no
checking OpenGL/gl.h presence... no
checking for OpenGL/gl.h... no
configure: Checking for OpenGL headers in /usr/X11R6
checking GL/gl.h usability... no
checking GL/gl.h presence... no
checking for GL/gl.h... no
configure: Checking for OpenGL headers in /usr/local
checking GL/gl.h usability... no
checking GL/gl.h presence... no
checking for GL/gl.h... no
configure: WARNING: No OpenGL headers found, wx will NOT be usable
checking GL/glu.h usability... no
checking GL/glu.h presence... no
checking for GL/glu.h... no
checking OpenGL/glu.h usability... no
checking OpenGL/glu.h presence... no
checking for OpenGL/glu.h... no
configure: WARNING: No GLU headers found, wx will NOT be usable
/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/./configure: line 5201: wx-config: command not found
checking for debug build of wxWidgets... checking for wx-config... no
checking for standard build of wxWidgets... checking for wx-config... (cached) no
configure: WARNING:
                wxWidgets must be installed on your system.

		Please check that wx-config is in path, the directory
		where wxWidgets libraries are installed (returned by
		'wx-config --libs' or 'wx-config --static --libs' command)
		is in LD_LIBRARY_PATH or equivalent variable and
		wxWidgets version is 2.8.4 or above.
checking if we can add -Werror=return-type to CFLAGS (via CFLAGS)... yes
checking if we can add -Werror=return-type to CXXFLAGS (via CFLAGS)... yes
configure: creating x86_64-unknown-linux-gnu/config.status
config.status: creating config.mk
config.status: creating c_src/Makefile
configure: configuring in erts
configure: running /bin/bash '/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/configure' --prefix=/usr/local  --cache-file=/dev/null --srcdir=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts
checking build system type... x86_64-unknown-linux-gnu
checking host system type... x86_64-unknown-linux-gnu
checking for gcc... gcc
checking for C compiler default output file name... a.out
checking whether the C compiler works... yes
checking whether we are cross compiling... no
checking for suffix of executables...
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ANSI C... none needed
checking for library containing strerror... none required
checking OTP release... 19
checking OTP version... 19.1
checking for gcc... (cached) gcc
checking whether we are using the GNU C compiler... (cached) yes
checking whether gcc accepts -g... (cached) yes
checking for gcc option to accept ANSI C... (cached) none needed
checking for mixed cygwin or msys and native VC++ environment... no
checking for mixed cygwin and native MinGW environment... no
checking if we mix cygwin with any native compiler... no
checking if we mix msys with another native compiler... no
checking for getconf... getconf
checking for large file support CFLAGS... none
checking for large file support LDFLAGS... none
checking for large file support LIBS... none
checking if we can add -Werror=return-type to WERRORFLAGS (via CFLAGS)... yes
checking if we can add -Werror=implicit to WERRORFLAGS (via CFLAGS)... yes
checking how to run the C preprocessor... gcc -E
checking for egrep... grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking for void *... yes
checking size of void *... 8
checking whether compilation mode forces ARCH adjustment... no
checking if VM has to be linked with Carbon framework... no
checking for rm... /bin/rm
checking for mkdir... /bin/mkdir
checking for cp... /bin/cp
checking if we are building a sharing-preserving emulator... no
checking how to run the C preprocessor... gcc -E
checking for ranlib... ranlib
checking for bison... bison -y
checking for perl5... no
checking for perl... /usr/bin/perl
checking whether ln -s works... yes
checking for ar... ar
checking for xsltproc... xsltproc
checking for fop... no
configure: WARNING: No 'fop' command found: going to generate placeholder PDF files
checking for xmllint... xmllint
checking for a BSD-compatible install... /usr/bin/install -c
checking how to create a directory including parents... /usr/bin/install -c -d
checking for extra flags needed to export symbols... -Wl,-export-dynamic
checking for sin in -lm... yes
checking for dlopen in -ldl... yes
checking for main in -linet... no
checking for openpty in -lutil... yes
checking for native win32 threads... no
checking for pthread_create in -lpthread... yes
checking for getconf... (cached) getconf
checking for Native POSIX Thread Library... yes
checking nptl/pthread.h usability... no
checking nptl/pthread.h presence... no
checking for nptl/pthread.h... no
checking pthread.h usability... yes
checking pthread.h presence... yes
checking for pthread.h... yes
checking pthread/mit/pthread.h usability... no
checking pthread/mit/pthread.h presence... no
checking for pthread/mit/pthread.h... no
checking for kstat_open in -lkstat... no
checking for clock_gettime(CLOCK_MONOTONIC_RAW, _)... yes
checking for clock_gettime() with custom monotonic clock type... CLOCK_MONOTONIC
checking for clock_getres... yes
checking for clock_get_attributes... no
checking for gethrtime... no
checking for mach clock_get_time() with monotonic clock type... no
checking for clock_gettime in -lrt... yes
checking if SIGUSR1 and SIGUSR2 can be used... yes
checking if sigaltstack can be used... yes
checking for pthread.h... (cached) yes
checking for pthread/mit/pthread.h... (cached) no
checking sched.h usability... yes
checking sched.h presence... yes
checking for sched.h... yes
checking sys/time.h usability... yes
checking sys/time.h presence... yes
checking for sys/time.h... yes
checking for pthread_spin_lock... yes
checking for sched_yield... yes
checking whether sched_yield() returns an int... yes
checking for pthread_yield... yes
checking whether pthread_yield() returns an int... yes
checking for pthread_rwlock_init... yes
checking for pthread_rwlockattr_setkind_np... yes
checking for PTHREAD_RWLOCK_PREFER_WRITER_NONRECURSIVE_NP... yes
checking for pthread_attr_setguardsize... yes
checking whether pthread_cond_timedwait() can use the monotonic clock CLOCK_MONOTONIC for timeout... yes
checking for Linux futexes... yes
checking for pthread_setname_np... linux
checking for pthread_getname_np... linux
checking for short... yes
checking size of short... 2
checking for int... yes
checking size of int... 4
checking for long... yes
checking size of long... 8
checking for long long... yes
checking size of long long... 8
checking for __int128_t... yes
checking size of __int128_t... 16
checking for a working __sync_synchronize()... yes
checking for 32-bit __sync_add_and_fetch()... yes
checking for 64-bit __sync_add_and_fetch()... yes
checking for 128-bit __sync_add_and_fetch()... no
checking for 32-bit __sync_fetch_and_and()... yes
checking for 64-bit __sync_fetch_and_and()... yes
checking for 128-bit __sync_fetch_and_and()... no
checking for 32-bit __sync_fetch_and_or()... yes
checking for 64-bit __sync_fetch_and_or()... yes
checking for 128-bit __sync_fetch_and_or()... no
checking for 32-bit __sync_val_compare_and_swap()... yes
checking for 64-bit __sync_val_compare_and_swap()... yes
checking for 128-bit __sync_val_compare_and_swap()... no
checking for 32-bit __atomic_store_n()... yes
checking for 64-bit __atomic_store_n()... yes
checking for 128-bit __atomic_store_n()... no
checking for 32-bit __atomic_load_n()... yes
checking for 64-bit __atomic_load_n()... yes
checking for 128-bit __atomic_load_n()... no
checking for 32-bit __atomic_add_fetch()... yes
checking for 64-bit __atomic_add_fetch()... yes
checking for 128-bit __atomic_add_fetch()... no
checking for 32-bit __atomic_fetch_and()... yes
checking for 64-bit __atomic_fetch_and()... yes
checking for 128-bit __atomic_fetch_and()... no
checking for 32-bit __atomic_fetch_or()... yes
checking for 64-bit __atomic_fetch_or()... yes
checking for 128-bit __atomic_fetch_or()... no
checking for 32-bit __atomic_compare_exchange_n()... yes
checking for 64-bit __atomic_compare_exchange_n()... yes
checking for 128-bit __atomic_compare_exchange_n()... no
checking for a usable libatomic_ops implementation... no
checking whether default stack size should be modified... no
checking for void *... (cached) yes
checking size of void *... (cached) 8
checking for int... (cached) yes
checking size of int... (cached) 4
checking for long... (cached) yes
checking size of long... (cached) 8
checking for long long... (cached) yes
checking size of long long... (cached) 8
checking for __int64... no
checking size of __int64... 0
checking for __int128_t... (cached) yes
checking size of __int128_t... (cached) 16
checking whether byte ordering is bigendian... no
checking whether double word ordering is middle-endian... no
checking for gcc cmpxchg16b plain asm support... yes
checking for gcc pic cmpxchg16b plain asm support... yes
checking whether an emulator with smp support should be built... yes
checking whether dirty schedulers should be enabled... no
checking whether the new code purge strategy should be enabled... no
checking for posix_fadvise... yes
checking for closefrom... no
checking linux/falloc.h usability... yes
checking linux/falloc.h presence... yes
checking for linux/falloc.h... yes
checking whether fallocate() works... yes
checking whether posix_fallocate() works... yes
checking whether the emulator should use threads... yes; thread support required and therefore forced
checking whether lock checking should be enabled... no
checking whether lock counters should be enabled... no
checking whether dlopen() needs to be called before first call to dlerror()... no
checking for kstat_open in -lkstat... (cached) no
checking for tgetent in -ltinfo... yes
checking for wcwidth... yes
checking for zlib 1.2.5 or higher... yes
checking for connect... yes
checking for gethostbyname... yes
checking for gethostbyname_r... yes
checking for working posix_openpt implementation... yes
checking if netdb.h requires netinet/in.h to be previously included... yes
checking for socklen_t... yes
checking for h_errno declaration in netdb.h... yes
checking for dirent.h that defines DIR... yes
checking for library containing opendir... none required
checking for ANSI C header files... (cached) yes
checking for sys/wait.h that is POSIX.1 compatible... yes
checking whether time.h and sys/time.h may both be included... yes
checking fcntl.h usability... yes
checking fcntl.h presence... yes
checking for fcntl.h... yes
checking limits.h usability... yes
checking limits.h presence... yes
checking for limits.h... yes
checking for unistd.h... (cached) yes
checking syslog.h usability... yes
checking syslog.h presence... yes
checking for syslog.h... yes
checking dlfcn.h usability... yes
checking dlfcn.h presence... yes
checking for dlfcn.h... yes
checking ieeefp.h usability... no
checking ieeefp.h presence... no
checking for ieeefp.h... no
checking for sys/types.h... (cached) yes
checking sys/stropts.h usability... yes
checking sys/stropts.h presence... yes
checking for sys/stropts.h... yes
checking sys/sysctl.h usability... yes
checking sys/sysctl.h presence... yes
checking for sys/sysctl.h... yes
checking sys/ioctl.h usability... yes
checking sys/ioctl.h presence... yes
checking for sys/ioctl.h... yes
checking for sys/time.h... (cached) yes
checking sys/uio.h usability... yes
checking sys/uio.h presence... yes
checking for sys/uio.h... yes
checking sys/socket.h usability... yes
checking sys/socket.h presence... yes
checking for sys/socket.h... yes
checking sys/sockio.h usability... no
checking sys/sockio.h presence... no
checking for sys/sockio.h... no
checking sys/socketio.h usability... no
checking sys/socketio.h presence... no
checking for sys/socketio.h... no
checking net/errno.h usability... no
checking net/errno.h presence... no
checking for net/errno.h... no
checking malloc.h usability... yes
checking malloc.h presence... yes
checking for malloc.h... yes
checking arpa/nameser.h usability... yes
checking arpa/nameser.h presence... yes
checking for arpa/nameser.h... yes
checking libdlpi.h usability... no
checking libdlpi.h presence... no
checking for libdlpi.h... no
checking pty.h usability... yes
checking pty.h presence... yes
checking for pty.h... yes
checking util.h usability... no
checking util.h presence... no
checking for util.h... no
checking libutil.h usability... no
checking libutil.h presence... no
checking for libutil.h... no
checking utmp.h usability... yes
checking utmp.h presence... yes
checking for utmp.h... yes
checking langinfo.h usability... yes
checking langinfo.h presence... yes
checking for langinfo.h... yes
checking poll.h usability... yes
checking poll.h presence... yes
checking for poll.h... yes
checking sdkddkver.h usability... no
checking sdkddkver.h presence... no
checking for sdkddkver.h... no
checking for struct ifreq.ifr_hwaddr... yes
checking for struct ifreq.ifr_enaddr... no
checking for dlpi_open in -ldlpi... no
configure: Extending the search to include /lib
checking for dlpi_open in -ldlpi... no
checking sys/resource.h usability... yes
checking sys/resource.h presence... yes
checking for sys/resource.h... yes
checking whether getrlimit is declared... yes
checking whether setrlimit is declared... yes
checking whether RLIMIT_STACK is declared... yes
checking sys/event.h usability... no
checking sys/event.h presence... no
checking for sys/event.h... no
checking sys/epoll.h usability... yes
checking sys/epoll.h presence... yes
checking for sys/epoll.h... yes
checking sys/devpoll.h usability... no
checking sys/devpoll.h presence... no
checking for sys/devpoll.h... no
checking sys/timerfd.h usability... yes
checking sys/timerfd.h presence... yes
checking for sys/timerfd.h... yes
checking for netinet/sctp.h... no
checking for sched.h... (cached) yes
checking setns.h usability... no
checking setns.h presence... no
checking for setns.h... no
checking for setns... yes
checking valgrind/valgrind.h usability... no
checking valgrind/valgrind.h presence... no
checking for valgrind/valgrind.h... no
checking for SO_BSDCOMPAT declaration... yes
checking for INADDR_LOOPBACK in netinet/in.h... yes
checking for sys_errlist declaration in stdio.h or errno.h... yes
checking if windows.h includes winsock2.h... no
checking for an ANSI C-conforming const... yes
checking return type of signal handlers... void
checking for off_t... yes
checking for pid_t... yes
checking for size_t... yes
checking whether struct tm is in sys/time.h or time.h... time.h
checking whether struct sockaddr has sa_len field... no
checking for struct exception (and matherr function)... yes
checking for char... yes
checking size of char... 1
checking for short... (cached) yes
checking size of short... (cached) 2
checking for int... (cached) yes
checking size of int... (cached) 4
checking for long... (cached) yes
checking size of long... (cached) 8
checking for void *... (cached) yes
checking size of void *... (cached) 8
checking for long long... (cached) yes
checking size of long long... (cached) 8
checking for size_t... (cached) yes
checking size of size_t... 8
checking for off_t... (cached) yes
checking size of off_t... 8
checking for time_t... yes
checking size of time_t... 8
checking if we should add -fno-tree-copyrename to CFLAGS for computed gotos to work properly... yes
checking for broken gcc-4.3.0 compiler... no
checking whether byte ordering is bigendian... (cached) no
checking whether double word ordering is middle-endian... (cached) no
checking for fdatasync... yes
checking for library containing fdatasync... none required
checking for sendfile... yes
checking windows.h usability... no
checking windows.h presence... no
checking for windows.h... no
checking winsock2.h usability... no
checking winsock2.h presence... no
checking for winsock2.h... no
checking for ws2tcpip.h... no
checking for getaddrinfo... yes
checking whether getaddrinfo accepts enough flags... yes
checking for getnameinfo... yes
checking for getipnodebyname... no
checking for getipnodebyaddr... no
checking for gethostbyname2... yes
checking for ieee_handler... no
checking for fpsetmask... no
checking for finite... yes
checking for isnan... yes
checking for isinf... yes
checking for res_gethostbyname... no
checking for dlopen... yes
checking for pread... yes
checking for pwrite... yes
checking for memmove... yes
checking for strerror... yes
checking for strerror_r... yes
checking for strncasecmp... yes
checking for gethrtime... (cached) no
checking for localtime_r... yes
checking for gmtime_r... yes
checking for inet_pton... yes
checking for mmap... yes
checking for mremap... yes
checking for memcpy... yes
checking for mallopt... yes
checking for sbrk... yes
checking for _sbrk... no
checking for __sbrk... yes
checking for brk... yes
checking for _brk... no
checking for __brk... no
checking for flockfile... yes
checking for fstat... yes
checking for strlcpy... no
checking for strlcat... no
checking for setsid... yes
checking for posix2time... no
checking for time2posix... no
checking for setlocale... yes
checking for nl_langinfo... yes
checking for poll... yes
checking for mlockall... yes
checking for ppoll... yes
checking for isfinite... yes
checking for posix_memalign... yes
checking for writev... yes
checking whether posix2time is declared... no
checking whether time2posix is declared... no
checking if vfork is known to hang multithreaded applications... no
checking for unistd.h... (cached) yes
checking vfork.h usability... no
checking vfork.h presence... no
checking for vfork.h... no
checking for fork... yes
checking for vfork... yes
checking for working fork... yes
checking for working vfork... (cached) yes
checking for vprintf... yes
checking for _doprnt... no
checking for conflicting declaration of fread... yes
checking for putc_unlocked... yes
checking for fwrite_unlocked... yes
checking for openpty... yes
checking net/if_dl.h usability... no
checking net/if_dl.h presence... no
checking for net/if_dl.h... no
checking ifaddrs.h usability... yes
checking ifaddrs.h presence... yes
checking for ifaddrs.h... yes
checking netpacket/packet.h usability... yes
checking netpacket/packet.h presence... yes
checking for netpacket/packet.h... yes
checking sys/un.h usability... yes
checking sys/un.h presence... yes
checking for sys/un.h... yes
checking for getifaddrs... yes
checking whether in6addr_any is declared... yes
checking whether in6addr_loopback is declared... yes
checking whether IN6ADDR_ANY_INIT is declared... yes
checking whether IN6ADDR_LOOPBACK_INIT is declared... yes
checking whether IPV6_V6ONLY is declared... yes
checking for sched_getaffinity/sched_setaffinity... yes
checking for pset functionality... no
checking for processor_bind functionality... no
checking for cpuset_getaffinity/cpuset_setaffinity... no
checking for 'end' symbol... yes
checking for '_end' symbol... yes
checking if __after_morecore_hook can track malloc()s core memory use... no
checking types of sbrk()s return value and argument... void *,intptr_t
checking types of brk()s return value and argument... int,void *
checking if sbrk()/brk() wrappers can track malloc()s core memory use... no
checking for IP version 6 support... yes
checking for multicast support... yes
checking for clock_gettime() with wall clock type... CLOCK_REALTIME
checking for clock_getres... (cached) yes
checking for clock_get_attributes... (cached) no
checking for gettimeofday... yes
checking for mach clock_get_time() with wall clock type... no
checking for clock_gettime(CLOCK_MONOTONIC_RAW, _)... (cached) yes
checking for clock_gettime() with custom monotonic clock type... CLOCK_MONOTONIC
checking for clock_getres... (cached) yes
checking for clock_get_attributes... (cached) no
checking for gethrtime... (cached) no
checking for mach clock_get_time() with monotonic clock type... (cached) no
checking for clock_gettime in -lrt... (cached) yes
checking for clock_gettime(CLOCK_MONOTONIC_RAW, _)... (cached) yes
checking for clock_gettime() with high resolution monotonic clock type... CLOCK_MONOTONIC
checking for clock_getres... (cached) yes
checking for clock_get_attributes... (cached) no
checking for gethrtime... (cached) no
checking for mach clock_get_time() with monotonic clock type... (cached) no
checking for clock_gettime in -lrt... (cached) yes
checking if gethrvtime works and how to use it... not working
checking if clock_gettime can be used to get process CPU time... yes
checking for m4... m4
checking whether MAP_FIXED is declared... yes
checking whether MAP_NORESERVE is declared... yes
configure: Floating point exceptions disabled by default on Linux
checking whether to redefine FD_SETSIZE... no
configure: Enable exec_alloc for hipe code allocation
checking for working poll()... yes
checking whether epoll is level triggered... yes
checking whether kernel poll support should be enabled... yes; epoll
checking whether putenv() stores a copy of the key-value pair... no
checking for ld... gcc
checking for compiler flags for loadable drivers... -g -O2 -I/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/x86_64-unknown-linux-gnu   -fno-tree-copyrename  -D_GNU_SOURCE -fPIC
checking for linker for loadable drivers... gcc
checking for linker flags for loadable drivers... -shared -Wl,-Bsymbolic
checking for 'runtime library path' linker flag... -Wl,-R
checking for a compiler that handles jumptables... gcc
checking for static ZLib to be used by SSL in standard locations... no
checking for OpenSSL >= 0.9.7 in standard locations... /usr
checking for OpenSSL kerberos 5 support... no
checking for ssl runtime library path to use... /usr/lib:/usr/local/lib64:/usr/sfw/lib64:/usr/lib64:/opt/local/lib64:/usr/pkg/lib64:/usr/local/openssl/lib64:/usr/lib/openssl/lib64:/usr/openssl/lib64:/usr/local/ssl/lib64:/usr/lib/ssl/lib64:/usr/ssl/lib64://lib64:/usr/local/lib:/usr/sfw/lib:/opt/local/lib:/usr/pkg/lib:/usr/local/openssl/lib:/usr/lib/openssl/lib:/usr/openssl/lib:/usr/local/ssl/lib:/usr/lib/ssl/lib:/usr/ssl/lib://lib
checking for kstat_open in -lkstat... (cached) no
checking for kvm_open in -lkvm... no
checking for javac.sh... no
checking for javac... javac
checking for JDK version 1.6... yes
checking for c++... c++
checking for log2... yes
configure: creating ./config.status
config.status: creating emulator/x86_64-unknown-linux-gnu/Makefile
config.status: creating epmd/src/x86_64-unknown-linux-gnu/Makefile
config.status: creating etc/common/x86_64-unknown-linux-gnu/Makefile
config.status: creating include/internal/x86_64-unknown-linux-gnu/ethread.mk
config.status: creating include/internal/x86_64-unknown-linux-gnu/erts_internal.mk
config.status: creating lib_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating Makefile
config.status: creating ../make/x86_64-unknown-linux-gnu/otp.mk
config.status: creating ../make/x86_64-unknown-linux-gnu/otp_ded.mk
config.status: creating ../make/make_emakefile
config.status: creating ../lib/ic/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating ../lib/os_mon/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating ../lib/crypto/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating ../lib/orber/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating ../lib/runtime_tools/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating ../lib/tools/c_src/x86_64-unknown-linux-gnu/Makefile
config.status: creating x86_64-unknown-linux-gnu/config.h
config.status: creating include/internal/x86_64-unknown-linux-gnu/ethread_header_config.h
config.status: creating include/x86_64-unknown-linux-gnu/erl_int_sizes_config.h
*********************************************************************
**********************  APPLICATIONS DISABLED  **********************
*********************************************************************

odbc           : ODBC library - link check failed

*********************************************************************
*********************************************************************
**********************  APPLICATIONS INFORMATION  *******************
*********************************************************************

wx             : wxWidgets not found, wx will NOT be usable

*********************************************************************
*********************************************************************
**********************  DOCUMENTATION INFORMATION  ******************
*********************************************************************

documentation  :
                 fop is missing.
                 Using fakefop to generate placeholder PDF files.

*********************************************************************
```
