### Installing

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ make install
 MAKE	emulator
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[4]: Nothing to be done for `etc'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[4]: Nothing to be done for `all'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
(cd preloaded/src && make ../ebin/erts.app)
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[2]: `../ebin/erts.app' is up to date.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
 MAKE	secondary_bootstrap_build
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
Makefile:72: warning: overriding commands for target `clean'
/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/make/otp_subdir.mk:29: warning: ignoring old commands for target `clean'
=== Entering application hipe
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
=== Leaving application hipe
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
=== Entering application parsetools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
=== Leaving application parsetools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[2]: Nothing to be done for `opt'.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
 MAKE	secondary_bootstrap_copy
 MAKE	tertiary_bootstrap_build
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
=== Entering application snmp
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
=== Leaving application snmp
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
=== Entering application sasl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
=== Leaving application sasl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
=== Entering application jinterface
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
=== Leaving application jinterface
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
=== Entering application ic
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[4]: Nothing to be done for `debug'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
=== Leaving application ic
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
=== Entering application syntax_tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
=== Leaving application syntax_tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
=== Entering application wx
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
=== Leaving application wx
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
 MAKE	tertiary_bootstrap_copy
test -d "/usr/local/bin" || /usr/bin/install -c -d "/usr/local/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang"
/usr/bin/install: cannot change permissions of ‘/usr/local/lib/erlang’: No such file or directory
make: *** [install.dirs] Error 1
```

### Trying with sudo

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ sudo make install
 MAKE	emulator
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[4]: Nothing to be done for `etc'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[4]: Nothing to be done for `all'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[3]: Nothing to be done for `all'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
(cd preloaded/src && make ../ebin/erts.app)
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[2]: `../ebin/erts.app' is up to date.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
 MAKE	secondary_bootstrap_build
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
Makefile:72: warning: overriding commands for target `clean'
/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/make/otp_subdir.mk:29: warning: ignoring old commands for target `clean'
=== Entering application hipe
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
=== Leaving application hipe
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
=== Entering application parsetools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
=== Leaving application parsetools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[2]: Nothing to be done for `opt'.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
 MAKE	secondary_bootstrap_copy
 MAKE	tertiary_bootstrap_build
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
=== Entering application snmp
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
=== Leaving application snmp
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
=== Entering application sasl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
=== Leaving application sasl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
=== Entering application jinterface
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
=== Leaving application jinterface
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
=== Entering application ic
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[4]: Nothing to be done for `debug'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
=== Leaving application ic
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
=== Entering application syntax_tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
=== Leaving application syntax_tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
=== Entering application wx
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
=== Leaving application wx
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
 MAKE	tertiary_bootstrap_copy
test -d "/usr/local/bin" || /usr/bin/install -c -d "/usr/local/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/lib"
cd erts && \
	  ERL_TOP=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1 PATH=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bootstrap/bin:"${PATH}" \
	  make TESTROOT="/usr/local/lib/erlang" release
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	release
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/man"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/doc"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 beam/erl_driver.h sys/unix/driver_int.h beam/erl_nif.h beam/erl_nif_api_funcs.h beam/erl_drv_nif.h "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 beam/erl_driver.h sys/unix/driver_int.h beam/erl_nif.h beam/erl_nif_api_funcs.h beam/erl_drv_nif.h "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/beam "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erl_child_setup "/usr/local/lib/erlang/erts-8.1/bin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	release
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/man"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/doc"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 beam/erl_driver.h sys/unix/driver_int.h beam/erl_nif.h beam/erl_nif_api_funcs.h beam/erl_drv_nif.h "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 beam/erl_driver.h sys/unix/driver_int.h beam/erl_nif.h beam/erl_nif_api_funcs.h beam/erl_drv_nif.h "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/beam.smp "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erl_child_setup "/usr/local/lib/erlang/erts-8.1/bin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c erl.src "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/inet_gethost /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/heart /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erlexec /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/typer /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/dialyzer /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erlc /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/escript /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/ct_run /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/run_erl /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/to_erl /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/dyn_erl "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c Install "/usr/local/lib/erlang"
/usr/bin/install -c -d "/usr/local/lib/erlang/misc"
/usr/bin/install -c ../unix/format_man_pages ../unix/makewhatis "/usr/local/lib/erlang/misc"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/src"
/usr/bin/install -c -m 644 ../unix/setuid_socket_wrap.c  "/usr/local/lib/erlang/erts-8.1/src"
/usr/bin/install -c ../unix/start.src ../unix/start_erl.src "/usr/local/lib/erlang/erts-8.1/bin"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
/usr/bin/install -c -d     "/usr/local/lib/erlang/erts-8.1/bin"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/epmd "/usr/local/lib/erlang/erts-8.1/bin"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	release
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 ../include/erl_memory_trace_parser.h ../include/x86_64-unknown-linux-gnu/erl_int_sizes_config.h ../include/erl_fixed_size_int_types.h "/usr/local/lib/erlang/erts-8.1/include"
/usr/bin/install -c -m 644 ../include/erl_memory_trace_parser.h ../include/x86_64-unknown-linux-gnu/erl_int_sizes_config.h ../include/erl_fixed_size_int_types.h "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/include/internal"
/usr/bin/install -c -m 644 ../include/internal/README ../include/internal/ethread.h ../include/internal/ethread_inline.h ../include/internal/ethr_mutex.h ../include/internal/ethr_optimized_fallbacks.h ../include/internal/ethr_atomics.h ../include/internal/x86_64-unknown-linux-gnu/ethread.mk ../include/internal/x86_64-unknown-linux-gnu/erts_internal.mk ../include/internal/x86_64-unknown-linux-gnu/ethread_header_config.h ../include/internal/erl_printf.h ../include/internal/erl_printf_format.h ../include/internal/erl_memory_trace_protocol.h ../include/internal/erl_misc_utils.h ../include/internal/erl_errno.h "/usr/local/lib/erlang/erts-8.1/include/internal"
for xdir in i386 x86_64 ppc32 sparc32 sparc64 tile gcc pthread win libatomic_ops; do \
		/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/include/internal/$xdir"; \
		/usr/bin/install -c -m 644 ../include/internal/$xdir/*.h \
			"/usr/local/lib/erlang/erts-8.1/include/internal/$xdir"; \
	done
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/lib"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/lib"
/usr/bin/install -c -m 644  ../lib/x86_64-unknown-linux-gnu/liberts.a ../lib/x86_64-unknown-linux-gnu/liberts_r.a "/usr/local/lib/erlang/erts-8.1/lib"
/usr/bin/install -c -m 644  ../lib/x86_64-unknown-linux-gnu/liberts.a ../lib/x86_64-unknown-linux-gnu/liberts_r.a "/usr/local/lib/erlang/usr/lib"
/usr/bin/install -c -d "/usr/local/lib/erlang/erts-8.1/lib/internal"
/usr/bin/install -c -m 644 ../lib/internal/README ../lib/internal/x86_64-unknown-linux-gnu/libethread.a  ../lib/internal/x86_64-unknown-linux-gnu/liberts_internal.a ../lib/internal/x86_64-unknown-linux-gnu/liberts_internal_r.a "/usr/local/lib/erlang/erts-8.1/lib/internal"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erts-8.1/src"
/usr/bin/install -c -m 644 erl_prim_loader.erl init.erl prim_file.erl prim_inet.erl zlib.erl prim_zip.erl otp_ring0.erl erts_code_purger.erl erlang.erl erts_internal.erl erl_tracer.erl erts_literal_area_collector.erl erts_dirty_process_code_checker.erl prim_eval.S prim_eval.erl "/usr/local/lib/erlang/lib/erts-8.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erts-8.1/ebin"
/usr/bin/install -c -m 644 ../ebin/erl_prim_loader.beam ../ebin/init.beam ../ebin/prim_file.beam ../ebin/prim_inet.beam ../ebin/zlib.beam ../ebin/prim_zip.beam ../ebin/otp_ring0.beam ../ebin/erts_code_purger.beam ../ebin/erlang.beam ../ebin/erts_internal.beam ../ebin/erl_tracer.beam ../ebin/erts_literal_area_collector.beam ../ebin/erts_dirty_process_code_checker.beam ../ebin/prim_eval.beam ../ebin/erts.app "/usr/local/lib/erlang/lib/erts-8.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded'
( make -f "/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/make/otp_released_app.mk"	\
		APP_PWD="/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts" APP_VSN=VSN APP=erts	\
		TESTROOT="/usr/local/lib/erlang" update)			\
	 || exit $?
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "erts-8.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep erts-8.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo erts-8.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
cd lib && \
	  ERL_TOP=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1 PATH=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bootstrap/bin:"${PATH}" \
	  make TESTROOT="/usr/local/lib/erlang" BUILD_ALL=true release
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
=== Entering application stdlib
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/stdlib-3.1/src"
/usr/bin/install -c -m 644 array.erl base64.erl beam_lib.erl binary.erl c.erl calendar.erl dets.erl dets_server.erl dets_sup.erl dets_utils.erl dets_v8.erl dets_v9.erl dict.erl digraph.erl digraph_utils.erl edlin.erl edlin_expand.erl epp.erl erl_anno.erl erl_bits.erl erl_compile.erl erl_eval.erl erl_expand_records.erl erl_internal.erl erl_lint.erl erl_parse.erl erl_posix_msg.erl erl_pp.erl erl_scan.erl erl_tar.erl error_logger_file_h.erl error_logger_tty_h.erl escript.erl ets.erl eval_bits.erl file_sorter.erl filelib.erl filename.erl gb_trees.erl gb_sets.erl gen.erl gen_event.erl gen_fsm.erl gen_server.erl gen_statem.erl io.erl io_lib.erl io_lib_format.erl io_lib_fread.erl io_lib_pretty.erl lib.erl lists.erl log_mf_h.erl maps.erl math.erl ms_transform.erl otp_internal.erl orddict.erl ordsets.erl re.erl pool.erl proc_lib.erl proplists.erl qlc.erl qlc_pt.erl queue.erl rand.erl random.erl sets.erl shell.erl shell_default.erl slave.erl sofs.erl string.erl supervisor.erl supervisor_bridge.erl sys.erl timer.erl unicode.erl win32reg.erl zip.erl erl_parse.yrl "/usr/local/lib/erlang/lib/stdlib-3.1/src"
/usr/bin/install -c -m 644 dets.hrl "/usr/local/lib/erlang/lib/stdlib-3.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/stdlib-3.1/include"
/usr/bin/install -c -m 644 ../include/assert.hrl ../include/erl_compile.hrl ../include/erl_bits.hrl ../include/ms_transform.hrl ../include/qlc.hrl ../include/zip.hrl "/usr/local/lib/erlang/lib/stdlib-3.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/stdlib-3.1/ebin"
/usr/bin/install -c -m 644 ../ebin/array.beam ../ebin/base64.beam ../ebin/beam_lib.beam ../ebin/binary.beam ../ebin/c.beam ../ebin/calendar.beam ../ebin/dets.beam ../ebin/dets_server.beam ../ebin/dets_sup.beam ../ebin/dets_utils.beam ../ebin/dets_v8.beam ../ebin/dets_v9.beam ../ebin/dict.beam ../ebin/digraph.beam ../ebin/digraph_utils.beam ../ebin/edlin.beam ../ebin/edlin_expand.beam ../ebin/epp.beam ../ebin/erl_anno.beam ../ebin/erl_bits.beam ../ebin/erl_compile.beam ../ebin/erl_eval.beam ../ebin/erl_expand_records.beam ../ebin/erl_internal.beam ../ebin/erl_lint.beam ../ebin/erl_parse.beam ../ebin/erl_posix_msg.beam ../ebin/erl_pp.beam ../ebin/erl_scan.beam ../ebin/erl_tar.beam ../ebin/error_logger_file_h.beam ../ebin/error_logger_tty_h.beam ../ebin/escript.beam ../ebin/ets.beam ../ebin/eval_bits.beam ../ebin/file_sorter.beam ../ebin/filelib.beam ../ebin/filename.beam ../ebin/gb_trees.beam ../ebin/gb_sets.beam ../ebin/gen.beam ../ebin/gen_event.beam ../ebin/gen_fsm.beam ../ebin/gen_server.beam ../ebin/gen_statem.beam ../ebin/io.beam ../ebin/io_lib.beam ../ebin/io_lib_format.beam ../ebin/io_lib_fread.beam ../ebin/io_lib_pretty.beam ../ebin/lib.beam ../ebin/lists.beam ../ebin/log_mf_h.beam ../ebin/maps.beam ../ebin/math.beam ../ebin/ms_transform.beam ../ebin/otp_internal.beam ../ebin/orddict.beam ../ebin/ordsets.beam ../ebin/re.beam ../ebin/pool.beam ../ebin/proc_lib.beam ../ebin/proplists.beam ../ebin/qlc.beam ../ebin/qlc_pt.beam ../ebin/queue.beam ../ebin/rand.beam ../ebin/random.beam ../ebin/sets.beam ../ebin/shell.beam ../ebin/shell_default.beam ../ebin/slave.beam ../ebin/sofs.beam ../ebin/string.beam ../ebin/supervisor.beam ../ebin/supervisor_bridge.beam ../ebin/sys.beam ../ebin/timer.beam ../ebin/unicode.beam ../ebin/win32reg.beam ../ebin/zip.beam ../ebin/stdlib.app ../ebin/stdlib.appup "/usr/local/lib/erlang/lib/stdlib-3.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/stdlib-3.1/examples"
/usr/bin/install -c -m 644 erl_id_trans.erl "/usr/local/lib/erlang/lib/stdlib-3.1/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "stdlib-3.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep stdlib-3.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo stdlib-3.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
=== Leaving application stdlib
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
=== Entering application sasl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/sasl-3.0.1/src"
/usr/bin/install -c -m 644 alarm_handler.erl sasl.erl sasl_report.erl sasl_report_file_h.erl sasl_report_tty_h.erl format_lib_supp.erl misc_supp.erl rb.erl rb_format_supp.erl release_handler.erl release_handler_1.erl si.erl si_sasl_supp.erl systools.erl systools_make.erl systools_rc.erl systools_relup.erl systools_lib.erl erlsrv.erl "/usr/local/lib/erlang/lib/sasl-3.0.1/src"
/usr/bin/install -c -m 644 systools.hrl "/usr/local/lib/erlang/lib/sasl-3.0.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/sasl-3.0.1/ebin"
/usr/bin/install -c -m 644 ../ebin/alarm_handler.beam ../ebin/sasl.beam ../ebin/sasl_report.beam ../ebin/sasl_report_file_h.beam ../ebin/sasl_report_tty_h.beam ../ebin/format_lib_supp.beam ../ebin/misc_supp.beam ../ebin/rb.beam ../ebin/rb_format_supp.beam ../ebin/release_handler.beam ../ebin/release_handler_1.beam ../ebin/si.beam ../ebin/si_sasl_supp.beam ../ebin/systools.beam ../ebin/systools_make.beam ../ebin/systools_rc.beam ../ebin/systools_relup.beam ../ebin/systools_lib.beam ../ebin/erlsrv.beam ../ebin/sasl.app ../ebin/sasl.appup "/usr/local/lib/erlang/lib/sasl-3.0.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/sasl-3.0.1/examples/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/sasl-3.0.1/examples/ebin"
(cd ..; tar cf - src ebin  | (cd "/usr/local/lib/erlang/lib/sasl-3.0.1/examples"; tar xf -))
chmod -R ug+w "/usr/local/lib/erlang/lib/sasl-3.0.1/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl/examples/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "sasl-3.0.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep sasl-3.0.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo sasl-3.0.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
=== Leaving application sasl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/sasl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
=== Entering application kernel
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/kernel-5.1/src"
/usr/bin/install -c -m 644 application.erl application_controller.erl application_master.erl application_starter.erl auth.erl code.erl code_server.erl disk_log.erl disk_log_1.erl disk_log_server.erl disk_log_sup.erl dist_ac.erl dist_util.erl erl_boot_server.erl erl_ddll.erl erl_distribution.erl erl_epmd.erl erl_reply.erl erts_debug.erl error_handler.erl error_logger.erl file.erl file_io_server.erl file_server.erl gen_tcp.erl gen_udp.erl gen_sctp.erl global.erl global_group.erl global_search.erl group.erl heart.erl hipe_unified_loader.erl inet.erl inet6_tcp.erl inet6_tcp_dist.erl inet6_udp.erl inet6_sctp.erl inet_config.erl inet_db.erl inet_dns.erl inet_gethost_native.erl inet_hosts.erl inet_parse.erl inet_res.erl inet_tcp.erl inet_tcp_dist.erl inet_udp.erl inet_sctp.erl kernel.erl kernel_config.erl local_udp.erl local_tcp.erl net.erl net_adm.erl net_kernel.erl os.erl pg2.erl ram_file.erl rpc.erl seq_trace.erl standard_error.erl user.erl user_drv.erl user_sup.erl wrap_log_reader.erl "/usr/local/lib/erlang/lib/kernel-5.1/src"
/usr/bin/install -c -m 644 application_master.hrl disk_log.hrl erl_epmd.hrl hipe_ext_format.hrl inet_dns.hrl inet_res.hrl inet_boot.hrl inet_config.hrl inet_int.hrl inet_dns_record_adts.hrl "/usr/local/lib/erlang/lib/kernel-5.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/kernel-5.1/include"
/usr/bin/install -c -m 644 ../include/file.hrl ../include/inet.hrl ../include/inet_sctp.hrl ../include/dist.hrl ../include/dist_util.hrl ../include/net_address.hrl  "/usr/local/lib/erlang/lib/kernel-5.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/kernel-5.1/ebin"
/usr/bin/install -c -m 644 ../ebin/application.beam ../ebin/application_controller.beam ../ebin/application_master.beam ../ebin/application_starter.beam ../ebin/auth.beam ../ebin/code.beam ../ebin/code_server.beam ../ebin/disk_log.beam ../ebin/disk_log_1.beam ../ebin/disk_log_server.beam ../ebin/disk_log_sup.beam ../ebin/dist_ac.beam ../ebin/dist_util.beam ../ebin/erl_boot_server.beam ../ebin/erl_ddll.beam ../ebin/erl_distribution.beam ../ebin/erl_epmd.beam ../ebin/erl_reply.beam ../ebin/erts_debug.beam ../ebin/error_handler.beam ../ebin/error_logger.beam ../ebin/file.beam ../ebin/file_io_server.beam ../ebin/file_server.beam ../ebin/gen_tcp.beam ../ebin/gen_udp.beam ../ebin/gen_sctp.beam ../ebin/global.beam ../ebin/global_group.beam ../ebin/global_search.beam ../ebin/group.beam ../ebin/heart.beam ../ebin/hipe_unified_loader.beam ../ebin/inet.beam ../ebin/inet6_tcp.beam ../ebin/inet6_tcp_dist.beam ../ebin/inet6_udp.beam ../ebin/inet6_sctp.beam ../ebin/inet_config.beam ../ebin/inet_db.beam ../ebin/inet_dns.beam ../ebin/inet_gethost_native.beam ../ebin/inet_hosts.beam ../ebin/inet_parse.beam ../ebin/inet_res.beam ../ebin/inet_tcp.beam ../ebin/inet_tcp_dist.beam ../ebin/inet_udp.beam ../ebin/inet_sctp.beam ../ebin/kernel.beam ../ebin/kernel_config.beam ../ebin/local_udp.beam ../ebin/local_tcp.beam ../ebin/net.beam ../ebin/net_adm.beam ../ebin/net_kernel.beam ../ebin/os.beam ../ebin/pg2.beam ../ebin/ram_file.beam ../ebin/rpc.beam ../ebin/seq_trace.beam ../ebin/standard_error.beam ../ebin/user.beam ../ebin/user_drv.beam ../ebin/user_sup.beam ../ebin/wrap_log_reader.beam ../ebin/kernel.app ../ebin/kernel.appup "/usr/local/lib/erlang/lib/kernel-5.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/kernel-5.1/examples"
tar cf - uds_dist | \
	(cd "/usr/local/lib/erlang/lib/kernel-5.1/examples"; tar xf - ; chmod -R ug+w uds_dist )
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "kernel-5.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep kernel-5.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo kernel-5.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
=== Leaving application kernel
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
=== Entering application compiler
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/compiler-7.0.2/src"
/usr/bin/install -c -m 644 beam_a.erl beam_asm.erl beam_block.erl beam_bool.erl beam_bs.erl beam_bsm.erl beam_clean.erl beam_dead.erl beam_dict.erl beam_disasm.erl beam_except.erl beam_flatten.erl beam_jump.erl beam_listing.erl beam_opcodes.erl beam_peep.erl beam_receive.erl beam_reorder.erl beam_split.erl beam_trim.erl beam_type.erl beam_utils.erl beam_validator.erl beam_z.erl cerl.erl cerl_clauses.erl cerl_inline.erl cerl_sets.erl cerl_trees.erl compile.erl core_lib.erl core_lint.erl core_parse.erl core_pp.erl core_scan.erl erl_bifs.erl rec_env.erl sys_core_dsetel.erl sys_core_fold.erl sys_core_fold_lists.erl sys_core_inline.erl sys_pre_attributes.erl sys_pre_expand.erl v3_codegen.erl v3_core.erl v3_kernel.erl v3_kernel_pp.erl v3_life.erl beam_disasm.hrl core_parse.hrl v3_kernel.hrl v3_life.hrl ./beam_opcodes.hrl \
		core_parse.yrl "/usr/local/lib/erlang/lib/compiler-7.0.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/compiler-7.0.2/ebin"
/usr/bin/install -c -m 644 ../ebin/beam_a.beam ../ebin/beam_asm.beam ../ebin/beam_block.beam ../ebin/beam_bool.beam ../ebin/beam_bs.beam ../ebin/beam_bsm.beam ../ebin/beam_clean.beam ../ebin/beam_dead.beam ../ebin/beam_dict.beam ../ebin/beam_disasm.beam ../ebin/beam_except.beam ../ebin/beam_flatten.beam ../ebin/beam_jump.beam ../ebin/beam_listing.beam ../ebin/beam_opcodes.beam ../ebin/beam_peep.beam ../ebin/beam_receive.beam ../ebin/beam_reorder.beam ../ebin/beam_split.beam ../ebin/beam_trim.beam ../ebin/beam_type.beam ../ebin/beam_utils.beam ../ebin/beam_validator.beam ../ebin/beam_z.beam ../ebin/cerl.beam ../ebin/cerl_clauses.beam ../ebin/cerl_inline.beam ../ebin/cerl_sets.beam ../ebin/cerl_trees.beam ../ebin/compile.beam ../ebin/core_lib.beam ../ebin/core_lint.beam ../ebin/core_parse.beam ../ebin/core_pp.beam ../ebin/core_scan.beam ../ebin/erl_bifs.beam ../ebin/rec_env.beam ../ebin/sys_core_dsetel.beam ../ebin/sys_core_fold.beam ../ebin/sys_core_fold_lists.beam ../ebin/sys_core_inline.beam ../ebin/sys_pre_attributes.beam ../ebin/sys_pre_expand.beam ../ebin/v3_codegen.beam ../ebin/v3_core.beam ../ebin/v3_kernel.beam ../ebin/v3_kernel_pp.beam ../ebin/v3_life.beam ../ebin/compiler.app ../ebin/compiler.appup "/usr/local/lib/erlang/lib/compiler-7.0.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "compiler-7.0.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep compiler-7.0.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo compiler-7.0.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
=== Leaving application compiler
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
=== Entering application tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/c_src"
/usr/bin/install -c -m 644 erl_memory.c erl_memory_trace_block_table.c erl_memory_trace_block_table.h "/usr/local/lib/erlang/lib/tools-2.8.6/c_src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/bin"
/usr/bin/install -c  ../bin/x86_64-unknown-linux-gnu/emem "/usr/local/lib/erlang/lib/tools-2.8.6/bin"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/src"
/usr/bin/install -c -m 644 cover.erl eprof.erl fprof.erl cprof.erl lcnt.erl instrument.erl make.erl tags.erl xref.erl xref_base.erl xref_compiler.erl xref_parser.erl xref_reader.erl xref_scanner.erl xref_utils.erl xref_parser.yrl xref.hrl "/usr/local/lib/erlang/lib/tools-2.8.6/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/ebin"
/usr/bin/install -c -m 644 ../ebin/cover.beam ../ebin/eprof.beam ../ebin/fprof.beam ../ebin/cprof.beam ../ebin/lcnt.beam ../ebin/instrument.beam ../ebin/make.beam ../ebin/tags.beam ../ebin/xref.beam ../ebin/xref_base.beam ../ebin/xref_compiler.beam ../ebin/xref_parser.beam ../ebin/xref_reader.beam ../ebin/xref_scanner.beam ../ebin/xref_utils.beam ../ebin/tools.app ../ebin/tools.appup \
		"/usr/local/lib/erlang/lib/tools-2.8.6/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/examples"
/usr/bin/install -c -m 644 xref_examples.erl "/usr/local/lib/erlang/lib/tools-2.8.6/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/tools-2.8.6/emacs"
/usr/bin/install -c -m 644 erlang-skels.el erlang-skels-old.el erlang_appwiz.el erlang-start.el erlang-eunit.el erlang-flymake.el erlang.el README test.erl.indented test.erl.orig \
		"/usr/local/lib/erlang/lib/tools-2.8.6/emacs"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "tools-2.8.6" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep tools-2.8.6 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo tools-2.8.6 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
=== Leaving application tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
=== Entering application common_test
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/common_test-1.12.3/src"
/usr/bin/install -c -m 644 ct.erl ct_logs.erl ct_framework.erl ct_ftp.erl ct_ssh.erl ct_snmp.erl ct_gen_conn.erl ct_rpc.erl ct_run.erl ct_master.erl ct_telnet.erl ct_util.erl ct_cover.erl ct_testspec.erl ct_event.erl ct_master_event.erl ct_master_logs.erl ct_master_status.erl ct_repeat.erl ct_telnet_client.erl ct_make.erl vts.erl ct_webtool.erl ct_webtool_sup.erl unix_telnet.erl ct_config.erl ct_config_plain.erl ct_config_xml.erl ct_slave.erl ct_hooks.erl ct_hooks_lock.erl cth_log_redirect.erl cth_surefire.erl ct_netconfc.erl ct_conn_log_h.erl cth_conn_log.erl ct_groups.erl ct_property_test.erl ct_release_test.erl erl2html2.erl test_server_ctrl.erl test_server_gl.erl test_server_io.erl test_server_node.erl test_server.erl test_server_sup.erl ct_util.hrl ct_netconfc.hrl "/usr/local/lib/erlang/lib/common_test-1.12.3/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/common_test-1.12.3/ebin"
/usr/bin/install -c -m 644  ../ebin/ct.beam ../ebin/ct_logs.beam ../ebin/ct_framework.beam ../ebin/ct_ftp.beam ../ebin/ct_ssh.beam ../ebin/ct_snmp.beam ../ebin/ct_gen_conn.beam ../ebin/ct_rpc.beam ../ebin/ct_run.beam ../ebin/ct_master.beam ../ebin/ct_telnet.beam ../ebin/ct_util.beam ../ebin/ct_cover.beam ../ebin/ct_testspec.beam ../ebin/ct_event.beam ../ebin/ct_master_event.beam ../ebin/ct_master_logs.beam ../ebin/ct_master_status.beam ../ebin/ct_repeat.beam ../ebin/ct_telnet_client.beam ../ebin/ct_make.beam ../ebin/vts.beam ../ebin/ct_webtool.beam ../ebin/ct_webtool_sup.beam ../ebin/unix_telnet.beam ../ebin/ct_config.beam ../ebin/ct_config_plain.beam ../ebin/ct_config_xml.beam ../ebin/ct_slave.beam ../ebin/ct_hooks.beam ../ebin/ct_hooks_lock.beam ../ebin/cth_log_redirect.beam ../ebin/cth_surefire.beam ../ebin/ct_netconfc.beam ../ebin/ct_conn_log_h.beam ../ebin/cth_conn_log.beam ../ebin/ct_groups.beam ../ebin/ct_property_test.beam ../ebin/ct_release_test.beam ../ebin/erl2html2.beam ../ebin/test_server_ctrl.beam ../ebin/test_server_gl.beam ../ebin/test_server_io.beam ../ebin/test_server_node.beam ../ebin/test_server.beam ../ebin/test_server_sup.beam ../ebin/common_test.app ../ebin/common_test.appup "/usr/local/lib/erlang/lib/common_test-1.12.3/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/common_test-1.12.3/include"
/usr/bin/install -c -m 644 ../include/ct.hrl ../include/ct_event.hrl "/usr/local/lib/erlang/lib/common_test-1.12.3/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/common_test-1.12.3/priv"
/usr/bin/install -c -m 644 vts.tool tile1.jpg ct_default.css jquery-latest.js jquery.tablesorter.min.js  "/usr/local/lib/erlang/lib/common_test-1.12.3/priv"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "common_test-1.12.3" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep common_test-1.12.3 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo common_test-1.12.3 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
=== Leaving application common_test
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
=== Entering application runtime_tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/src"
/usr/bin/install -c -m 644 appmon_info.erl erts_alloc_config.erl runtime_tools.erl runtime_tools_sup.erl dbg.erl dyntrace.erl percept_profile.erl system_information.erl observer_backend.erl ttb_autostart.erl msacc.erl "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/include"
/usr/bin/install -c -m 644 ../include/observer_backend.hrl "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/examples"
/usr/bin/install -c -m 644 ../examples/* "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/ebin"
/usr/bin/install -c -m 644 ../ebin/appmon_info.beam ../ebin/erts_alloc_config.beam ../ebin/runtime_tools.beam ../ebin/runtime_tools_sup.beam ../ebin/dbg.beam ../ebin/dyntrace.beam ../ebin/percept_profile.beam ../ebin/system_information.beam ../ebin/observer_backend.beam ../ebin/ttb_autostart.beam ../ebin/msacc.beam ../ebin/runtime_tools.app ../ebin/runtime_tools.appup "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/priv/lib"
/usr/bin/install -c  ../priv/lib/x86_64-unknown-linux-gnu/dyntrace.so  ../priv/lib/x86_64-unknown-linux-gnu/trace_file_drv.so  ../priv/lib/x86_64-unknown-linux-gnu/trace_ip_drv.so "/usr/local/lib/erlang/lib/runtime_tools-1.10.1/priv/lib"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "runtime_tools-1.10.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep runtime_tools-1.10.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo runtime_tools-1.10.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
=== Leaving application runtime_tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
=== Entering application inets
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/inets_app"
/usr/bin/install -c -m 644 inets_internal.hrl inets.erl inets_service.erl inets_app.erl inets_sup.erl inets_trace.erl inets_lib.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/inets_app"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/include"
/usr/bin/install -c -m 644 ../../include/httpd.hrl ../../include/mod_auth.hrl "/usr/local/lib/erlang/lib/inets-6.3.3/include"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/inets.beam ../../ebin/inets_service.beam ../../ebin/inets_app.beam ../../ebin/inets_sup.beam ../../ebin/inets_trace.beam ../../ebin/inets_lib.beam ../../ebin/inets.app ../../ebin/inets.appup "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_lib"
/usr/bin/install -c -m 644 http_internal.hrl http_chunk.erl http_transport.erl http_util.erl http_request.erl http_response.erl http_uri.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_lib"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/http_chunk.beam ../../ebin/http_transport.beam ../../ebin/http_util.beam ../../ebin/http_request.beam ../../ebin/http_response.beam ../../ebin/http_uri.beam  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_client"
/usr/bin/install -c -m 644 httpc_internal.hrl httpc.erl httpc_cookie.erl httpc_handler.erl httpc_manager.erl httpc_sup.erl httpc_handler_sup.erl httpc_profile_sup.erl httpc_response.erl httpc_request.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_client"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/httpc.beam ../../ebin/httpc_cookie.beam ../../ebin/httpc_handler.beam ../../ebin/httpc_manager.beam ../../ebin/httpc_sup.beam ../../ebin/httpc_handler_sup.beam ../../ebin/httpc_profile_sup.beam ../../ebin/httpc_response.beam ../../ebin/httpc_request.beam  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_server"
/usr/bin/install -c -m 644 httpd.hrl httpd_internal.hrl mod_auth.hrl httpd.erl httpd_acceptor.erl httpd_acceptor_sup.erl httpd_connection_sup.erl httpd_cgi.erl httpd_conf.erl httpd_custom.erl httpd_example.erl httpd_esi.erl httpd_file.erl httpd_instance_sup.erl httpd_log.erl httpd_manager.erl httpd_misc_sup.erl httpd_request.erl httpd_request_handler.erl httpd_response.erl httpd_script_env.erl httpd_socket.erl httpd_sup.erl httpd_util.erl mod_actions.erl mod_alias.erl mod_auth.erl mod_auth_plain.erl mod_auth_dets.erl mod_auth_mnesia.erl mod_auth_server.erl mod_browser.erl mod_cgi.erl mod_dir.erl mod_disk_log.erl mod_esi.erl mod_get.erl mod_head.erl mod_htaccess.erl mod_log.erl mod_range.erl mod_responsecontrol.erl mod_trace.erl mod_security.erl mod_security_server.erl httpd_custom_api.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/http_server"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/httpd.beam ../../ebin/httpd_acceptor.beam ../../ebin/httpd_acceptor_sup.beam ../../ebin/httpd_connection_sup.beam ../../ebin/httpd_cgi.beam ../../ebin/httpd_conf.beam ../../ebin/httpd_custom.beam ../../ebin/httpd_example.beam ../../ebin/httpd_esi.beam ../../ebin/httpd_file.beam ../../ebin/httpd_instance_sup.beam ../../ebin/httpd_log.beam ../../ebin/httpd_manager.beam ../../ebin/httpd_misc_sup.beam ../../ebin/httpd_request.beam ../../ebin/httpd_request_handler.beam ../../ebin/httpd_response.beam ../../ebin/httpd_script_env.beam ../../ebin/httpd_socket.beam ../../ebin/httpd_sup.beam ../../ebin/httpd_util.beam ../../ebin/mod_actions.beam ../../ebin/mod_alias.beam ../../ebin/mod_auth.beam ../../ebin/mod_auth_plain.beam ../../ebin/mod_auth_dets.beam ../../ebin/mod_auth_mnesia.beam ../../ebin/mod_auth_server.beam ../../ebin/mod_browser.beam ../../ebin/mod_cgi.beam ../../ebin/mod_dir.beam ../../ebin/mod_disk_log.beam ../../ebin/mod_esi.beam ../../ebin/mod_get.beam ../../ebin/mod_head.beam ../../ebin/mod_htaccess.beam ../../ebin/mod_log.beam ../../ebin/mod_range.beam ../../ebin/mod_responsecontrol.beam ../../ebin/mod_trace.beam ../../ebin/mod_security.beam ../../ebin/mod_security_server.beam  ../../ebin/httpd_custom_api.beam "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/ftp"
/usr/bin/install -c -m 644 ftp_internal.hrl ftp.erl ftp_progress.erl ftp_response.erl ftp_sup.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/ftp"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/ftp.beam ../../ebin/ftp_progress.beam ../../ebin/ftp_response.beam ../../ebin/ftp_sup.beam "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/src/tftp"
/usr/bin/install -c -m 644 tftp.hrl tftp_binary.erl tftp_engine.erl tftp_file.erl tftp_lib.erl tftp_logger.erl tftp_sup.erl tftp.erl "/usr/local/lib/erlang/lib/inets-6.3.3/src/tftp"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
/usr/bin/install -c -m 644 ../../ebin/tftp_binary.beam ../../ebin/tftp_engine.beam ../../ebin/tftp_file.beam ../../ebin/tftp_lib.beam ../../ebin/tftp_logger.beam ../../ebin/tftp_sup.beam ../../ebin/tftp.beam "/usr/local/lib/erlang/lib/inets-6.3.3/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/auth"
/usr/bin/install -c -m 644 auth/group auth/passwd  "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/auth"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/cgi-bin"
/usr/bin/install -c cgi-bin/printenv.sh  "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/cgi-bin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/conf"
/usr/bin/install -c -m 644 conf/8080.conf conf/8888.conf conf/httpd.conf conf/ssl.conf conf/mime.types  "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/conf"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/open"
/usr/bin/install -c -m 644 htdocs/open/dummy.html  \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/open"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/mnesia_open"
/usr/bin/install -c -m 644 htdocs/mnesia_open/dummy.html  \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/mnesia_open"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/misc"
/usr/bin/install -c -m 644 htdocs/misc/friedrich.html htdocs/misc/oech.html \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/misc"
/usr/bin/install -c -d  \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/secret/top_secret"
/usr/bin/install -c -d  \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/mnesia_secret/top_secret"
/usr/bin/install -c -m 644 htdocs/secret/dummy.html   \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/secret"
/usr/bin/install -c -m 644 htdocs/mnesia_secret/dummy.html   \
		"/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs/mnesia_secret"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs"
/usr/bin/install -c -m 644 htdocs/index.html htdocs/config.shtml htdocs/echo.shtml htdocs/exec.shtml htdocs/flastmod.shtml htdocs/fsize.shtml htdocs/include.shtml "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/htdocs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/icons"
/usr/bin/install -c -m 644 icons/README icons/a.gif icons/alert.black.gif icons/alert.red.gif icons/apache_pb.gif icons/back.gif icons/ball.gray.gif icons/ball.red.gif icons/binary.gif icons/binhex.gif icons/blank.gif icons/bomb.gif icons/box1.gif icons/box2.gif icons/broken.gif icons/burst.gif icons/button1.gif icons/button10.gif icons/button2.gif icons/button3.gif icons/button4.gif icons/button5.gif icons/button6.gif icons/button7.gif icons/button8.gif icons/button9.gif icons/buttonl.gif icons/buttonr.gif icons/c.gif icons/comp.blue.gif icons/comp.gray.gif icons/compressed.gif icons/continued.gif icons/dir.gif icons/down.gif icons/dvi.gif icons/f.gif icons/folder.gif icons/folder.open.gif icons/folder.sec.gif icons/forward.gif icons/generic.gif icons/generic.red.gif icons/generic.sec.gif icons/hand.right.gif icons/hand.up.gif icons/htdig.gif icons/icon.sheet.gif icons/image1.gif icons/image2.gif icons/image3.gif icons/index.gif icons/layout.gif icons/left.gif icons/link.gif icons/movie.gif icons/p.gif icons/patch.gif icons/pdf.gif icons/pie0.gif icons/pie1.gif icons/pie2.gif icons/pie3.gif icons/pie4.gif icons/pie5.gif icons/pie6.gif icons/pie7.gif icons/pie8.gif icons/portal.gif icons/poweredby.gif icons/ps.gif icons/quill.gif icons/right.gif icons/screw1.gif icons/screw2.gif icons/script.gif icons/sound1.gif icons/sound2.gif icons/sphere1.gif icons/sphere2.gif icons/star.gif icons/star_blank.gif icons/tar.gif icons/tex.gif icons/text.gif icons/transfer.gif icons/unknown.gif icons/up.gif icons/uu.gif icons/uuencoded.gif icons/world1.gif icons/world2.gif "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/icons"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/ssl"
/usr/bin/install -c -m 644 ssl/ssl_client.pem ssl/ssl_server.pem "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/ssl"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/examples/server_root/logs"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/examples"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
/usr/bin/install -c -m 644 hdlt.sh.skel "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
/usr/bin/install -c -m 644 hdlt.config.skel   "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
/usr/bin/install -c -m 644 hdlt_ssl_client_cert.pem hdlt_ssl_server_cert.pem       "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
/usr/bin/install -c -m 644 ./hdlt.beam ./hdlt_ctrl.beam ./hdlt_client.beam ./hdlt_logger.beam ./hdlt_random_html.beam ./hdlt_server.beam ./hdlt_slave.beam     "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
/usr/bin/install -c -m 644 hdlt.erl hdlt_ctrl.erl hdlt_client.erl hdlt_logger.erl hdlt_random_html.erl hdlt_server.erl hdlt_slave.erl        "/usr/local/lib/erlang/lib/inets-6.3.3/examples"/httpd_load_test
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/inets-6.3.3/priv/bin"
/usr/bin/install -c bin/runcgi.sh "/usr/local/lib/erlang/lib/inets-6.3.3/priv/bin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "inets-6.3.3" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep inets-6.3.3 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo inets-6.3.3 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
=== Leaving application inets
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
=== Entering application parsetools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/parsetools-2.1.3/src"
/usr/bin/install -c -m 644 leex.erl yecc.erl yeccparser.erl yeccscan.erl "/usr/local/lib/erlang/lib/parsetools-2.1.3/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/parsetools-2.1.3/ebin"
/usr/bin/install -c -m 644 ../ebin/leex.beam ../ebin/yecc.beam ../ebin/yeccparser.beam ../ebin/yeccscan.beam ../ebin/parsetools.app ../ebin/parsetools.appup "/usr/local/lib/erlang/lib/parsetools-2.1.3/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/parsetools-2.1.3/include"
/usr/bin/install -c -m 644 ../include/yeccpre.hrl ../include/leexinc.hrl "/usr/local/lib/erlang/lib/parsetools-2.1.3/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "parsetools-2.1.3" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep parsetools-2.1.3 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo parsetools-2.1.3 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
=== Leaving application parsetools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/parsetools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
=== Entering application xmerl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/xmerl-1.3.12/ebin"
/usr/bin/install -c -m 644 ../ebin/xmerl_scan.beam ../ebin/xmerl.beam ../ebin/xmerl_xs.beam ../ebin/xmerl_eventp.beam ../ebin/xmerl_xpath.beam ../ebin/xmerl_xsd.beam ../ebin/xmerl_b64Bin.beam ../ebin/xmerl_b64Bin_scan.beam ../ebin/xmerl_html.beam ../ebin/xmerl_lib.beam ../ebin/xmerl_otpsgml.beam ../ebin/xmerl_regexp.beam ../ebin/xmerl_sgml.beam ../ebin/xmerl_simple.beam ../ebin/xmerl_text.beam ../ebin/xmerl_ucs.beam ../ebin/xmerl_uri.beam ../ebin/xmerl_validate.beam ../ebin/xmerl_xlate.beam ../ebin/xmerl_xml.beam ../ebin/xmerl_xpath_lib.beam ../ebin/xmerl_xpath_parse.beam ../ebin/xmerl_xpath_pred.beam ../ebin/xmerl_xpath_scan.beam ../ebin/xmerl_xsd_type.beam ../ebin/xmerl_sax_parser.beam ../ebin/xmerl_sax_parser_list.beam ../ebin/xmerl_sax_parser_latin1.beam ../ebin/xmerl_sax_parser_utf8.beam ../ebin/xmerl_sax_parser_utf16be.beam ../ebin/xmerl_sax_parser_utf16le.beam ../ebin/xmerl_sax_simple_dom.beam ../ebin/xmerl_sax_old_dom.beam ../ebin/xmerl.app ../ebin/xmerl.appup "/usr/local/lib/erlang/lib/xmerl-1.3.12/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/xmerl-1.3.12/src"
/usr/bin/install -c -m 644 xmerl_scan.erl xmerl.erl xmerl_xs.erl xmerl_eventp.erl xmerl_xpath.erl xmerl_xsd.erl xmerl_b64Bin.erl xmerl_b64Bin_scan.erl xmerl_html.erl xmerl_lib.erl xmerl_otpsgml.erl xmerl_regexp.erl xmerl_sgml.erl xmerl_simple.erl xmerl_text.erl xmerl_ucs.erl xmerl_uri.erl xmerl_validate.erl xmerl_xlate.erl xmerl_xml.erl xmerl_xpath_lib.erl xmerl_xpath_parse.erl xmerl_xpath_pred.erl xmerl_xpath_scan.erl xmerl_xsd_type.erl xmerl_sax_parser.erl xmerl_sax_parser_list.erl xmerl_sax_parser_latin1.erl xmerl_sax_parser_utf8.erl xmerl_sax_parser_utf16be.erl xmerl_sax_parser_utf16le.erl xmerl_sax_simple_dom.erl xmerl_sax_old_dom.erl xmerl_internal.hrl xmerl_sax_old_dom.hrl xmerl_sax_parser.hrl xmerl.app.src xmerl.appup.src "/usr/local/lib/erlang/lib/xmerl-1.3.12/src"
/usr/bin/install -c -m 644 xmerl_xpath_parse.yrl "/usr/local/lib/erlang/lib/xmerl-1.3.12/src"
/usr/bin/install -c -m 644 xmerl_b64Bin.yrl "/usr/local/lib/erlang/lib/xmerl-1.3.12/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/xmerl-1.3.12/include"
/usr/bin/install -c -m 644 ../include/xmerl.hrl ../include/xmerl_xpath.hrl ../include/xmerl_xsd.hrl "/usr/local/lib/erlang/lib/xmerl-1.3.12/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "xmerl-1.3.12" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep xmerl-1.3.12 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo xmerl-1.3.12 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
=== Leaving application xmerl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
=== Entering application edoc
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/edoc-0.8/ebin"
/usr/bin/install -c -m 644 ../ebin/edoc.beam ../ebin/edoc_data.beam ../ebin/edoc_doclet.beam ../ebin/edoc_extract.beam ../ebin/edoc_layout.beam ../ebin/edoc_lib.beam ../ebin/edoc_macros.beam ../ebin/edoc_parser.beam ../ebin/edoc_refs.beam ../ebin/edoc_report.beam ../ebin/edoc_run.beam ../ebin/edoc_scanner.beam ../ebin/edoc_specs.beam ../ebin/edoc_tags.beam ../ebin/edoc_types.beam ../ebin/edoc_wiki.beam ../ebin/otpsgml_layout.beam ../ebin/edoc.app ../ebin/edoc.appup "/usr/local/lib/erlang/lib/edoc-0.8/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/edoc-0.8/src"
/usr/bin/install -c -m 644 edoc.erl edoc_data.erl edoc_doclet.erl edoc_extract.erl edoc_layout.erl edoc_lib.erl edoc_macros.erl edoc_parser.erl edoc_refs.erl edoc_report.erl edoc_run.erl edoc_scanner.erl edoc_specs.erl edoc_tags.erl edoc_types.erl edoc_wiki.erl otpsgml_layout.erl edoc.hrl edoc_types.hrl ../include/edoc_doclet.hrl edoc_parser.yrl "/usr/local/lib/erlang/lib/edoc-0.8/src"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/edoc-0.8/include"
/usr/bin/install -c -m 644 edoc_doclet.hrl "/usr/local/lib/erlang/lib/edoc-0.8/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/edoc-0.8/priv"
/usr/bin/install -c -m 644 stylesheet.css erlang.png edoc.dtd "/usr/local/lib/erlang/lib/edoc-0.8/priv"
/usr/bin/install -c edoc_generate "/usr/local/lib/erlang/lib/edoc-0.8/priv"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "edoc-0.8" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep edoc-0.8 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo edoc-0.8 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
=== Leaving application edoc
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
=== Entering application erl_docgen
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/src"
/usr/bin/install -c -m 644 docgen_otp_specs.erl docgen_edoc_xml_cb.erl docgen_xmerl_xml_cb.erl "/usr/local/lib/erlang/lib/erl_docgen-0.6/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/ebin"
/usr/bin/install -c -m 644 ../ebin/docgen_otp_specs.beam ../ebin/docgen_edoc_xml_cb.beam ../ebin/docgen_xmerl_xml_cb.beam ../ebin/erl_docgen.app ../ebin/erl_docgen.appup "/usr/local/lib/erlang/lib/erl_docgen-0.6/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/bin"
/usr/bin/install -c codeline_preprocessing.escript xml_from_edoc.escript "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/bin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/css"
/usr/bin/install -c -m 644 otp_doc.css "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/css"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd"
/usr/bin/install -c -m 644 application.dtd chapter.dtd common.header.dtd comref.dtd fileref.dtd xhtml1-frameset.dtd appref.dtd cites.dtd common.image.dtd cref.dtd part.dtd xhtml1-strict.dtd book.dtd common.dtd common.refs.dtd erlref.dtd report.dtd xhtml1-transitional.dtd bookinsidecover.dtd common.entities.dtd common.table.dtd fascicules.dtd terms.dtd  xhtml-special.ent xhtml-symbol.ent "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd_html_entities"
/usr/bin/install -c -m 644 xhtml-lat1.ent "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd_html_entities"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd_man_entities"
/usr/bin/install -c -m 644 xhtml-lat1.ent "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/dtd_man_entities"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/images"
/usr/bin/install -c -m 644 erlang-logo.gif erlang-logo.png "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/images"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/js/flipmenu"
/usr/bin/install -c -m 644 flipmenu.js flip_closed.gif flip_open.gif flip_static.gif "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/js/flipmenu"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/xsl"
/usr/bin/install -c -m 644 db_pdf.xsl db_pdf_params.xsl db_html.xsl db_html_params.xsl db_man.xsl db_eix.xsl "/usr/local/lib/erlang/lib/erl_docgen-0.6/priv/xsl"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "erl_docgen-0.6" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep erl_docgen-0.6 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo erl_docgen-0.6 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
=== Leaving application erl_docgen
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
=== Entering application snmp
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/compiler"
/usr/bin/install -c -m 644 snmpc.src snmpc_mib_gram.yrl snmpc_mib_gram.erl snmpc.erl snmpc_lib.erl snmpc_mib_to_hrl.erl snmpc_misc.erl snmpc_tok.erl snmpc.hrl snmpc_lib.hrl snmpc_misc.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/compiler"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmpc_mib_gram.beam ../../ebin/snmpc.beam ../../ebin/snmpc_lib.beam ../../ebin/snmpc_mib_to_hrl.beam ../../ebin/snmpc_misc.beam ../../ebin/snmpc_tok.beam  "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/bin"
/usr/bin/install -c ../../bin/snmpc "/usr/local/lib/erlang/lib/snmp-5.2.4/bin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs/v1"
/usr/bin/install -c -m 644 RFC1213-MIB.mib STANDARD-MIB.mib SNMPv2-TM.mib SNMPv2-MIB.mib SNMP-FRAMEWORK-MIB.mib SNMP-MPD-MIB.mib SNMP-TARGET-MIB.mib SNMP-NOTIFICATION-MIB.mib SNMP-COMMUNITY-MIB.mib SNMP-USER-BASED-SM-MIB.mib SNMP-VIEW-BASED-ACM-MIB.mib SNMP-USM-AES-MIB.mib INET-ADDRESS-MIB.mib TRANSPORT-ADDRESS-MIB.mib OTP-SNMPEA-MIB.mib "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs"
/usr/bin/install -c -m 644 SNMPv2-SMI.mib SNMPv2-TC.mib SNMPv2-CONF.mib  "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs"
/usr/bin/install -c -m 644 STANDARD-MIB.funcs SNMPv2-MIB.funcs SNMP-NOTIFICATION-MIB.funcs SNMP-TARGET-MIB.funcs "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs"
/usr/bin/install -c -m 644 RFC1155-SMI.mib RFC-1212.mib RFC-1215.mib "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs/v1"
/usr/bin/install -c -m 644 v1/OTP-SNMPEA-MIB.mib.v1 "/usr/local/lib/erlang/lib/snmp-5.2.4/mibs/v1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/include"
/usr/bin/install -c -m 644 ../include/SNMPv2-TC.hrl ../include/RFC1213-MIB.hrl ../include/STANDARD-MIB.hrl ../include/SNMPv2-TM.hrl ../include/SNMPv2-MIB.hrl ../include/SNMP-FRAMEWORK-MIB.hrl ../include/SNMP-MPD-MIB.hrl ../include/SNMP-TARGET-MIB.hrl ../include/SNMP-NOTIFICATION-MIB.hrl ../include/SNMP-COMMUNITY-MIB.hrl ../include/SNMP-USER-BASED-SM-MIB.hrl ../include/SNMP-VIEW-BASED-ACM-MIB.hrl ../include/SNMP-USM-AES-MIB.hrl ../include/INET-ADDRESS-MIB.hrl ../include/TRANSPORT-ADDRESS-MIB.hrl ../include/OTP-SNMPEA-MIB.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/mibs"
/usr/bin/install -c -m 644 ../priv/mibs/RFC1213-MIB.bin ../priv/mibs/STANDARD-MIB.bin ../priv/mibs/SNMPv2-TM.bin ../priv/mibs/SNMPv2-MIB.bin ../priv/mibs/SNMP-FRAMEWORK-MIB.bin ../priv/mibs/SNMP-MPD-MIB.bin ../priv/mibs/SNMP-TARGET-MIB.bin ../priv/mibs/SNMP-NOTIFICATION-MIB.bin ../priv/mibs/SNMP-COMMUNITY-MIB.bin ../priv/mibs/SNMP-USER-BASED-SM-MIB.bin ../priv/mibs/SNMP-VIEW-BASED-ACM-MIB.bin ../priv/mibs/SNMP-USM-AES-MIB.bin ../priv/mibs/INET-ADDRESS-MIB.bin ../priv/mibs/TRANSPORT-ADDRESS-MIB.bin ../priv/mibs/OTP-SNMPEA-MIB.bin "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/mibs"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/compiler"
/usr/bin/install -c -m 644 snmpc.src snmpc_mib_gram.yrl snmpc_mib_gram.erl snmpc.erl snmpc_lib.erl snmpc_mib_to_hrl.erl snmpc_misc.erl snmpc_tok.erl snmpc.hrl snmpc_lib.hrl snmpc_misc.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/compiler"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmpc_mib_gram.beam ../../ebin/snmpc.beam ../../ebin/snmpc_lib.beam ../../ebin/snmpc_mib_to_hrl.beam ../../ebin/snmpc_misc.beam ../../ebin/snmpc_tok.beam  "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/bin"
/usr/bin/install -c ../../bin/snmpc "/usr/local/lib/erlang/lib/snmp-5.2.4/bin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/compile'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/app"
/usr/bin/install -c -m 644 snmp.erl snmp_app.erl snmp_app_sup.erl snmp_internal.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/app"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmp.beam ../../ebin/snmp_app.beam ../../ebin/snmp_app_sup.beam ../../ebin/snmp.app ../../ebin/snmp.appup \
		"/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/include"
/usr/bin/install -c -m 644 ../../include/snmp_types.hrl ../../include/snmp_tables.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/include"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/misc"
/usr/bin/install -c -m 644 snmp_conf.erl snmp_config.erl snmp_log.erl snmp_mini_mib.erl snmp_misc.erl snmp_note_store.erl snmp_pdus.erl snmp_usm.erl snmp_verbosity.erl snmp_verbosity.hrl snmp_debug.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/misc"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmp_conf.beam ../../ebin/snmp_config.beam ../../ebin/snmp_log.beam ../../ebin/snmp_mini_mib.beam ../../ebin/snmp_misc.beam ../../ebin/snmp_note_store.beam ../../ebin/snmp_pdus.beam ../../ebin/snmp_usm.beam ../../ebin/snmp_verbosity.beam "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/misc'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/agent"
/usr/bin/install -c -m 644 snmpa.erl snmpa_authentication_service.erl snmpa_discovery_handler.erl snmpa_error_report.erl snmpa_mib_storage.erl snmpa_mib_data.erl snmpa_network_interface.erl snmpa_network_interface_filter.erl snmpa_notification_delivery_info_receiver.erl snmpa_notification_filter.erl snmpa_set_mechanism.erl snmpa_acm.erl snmpa_agent.erl snmpa_agent_sup.erl snmpa_app.erl snmpa_conf.erl snmpa_discovery_handler_default.erl snmpa_error.erl snmpa_error_io.erl snmpa_error_logger.erl snmpa_local_db.erl snmpa_mib_storage_ets.erl snmpa_mib_storage_dets.erl snmpa_mib_storage_mnesia.erl snmpa_mib.erl snmpa_mib_data_tttn.erl snmpa_mib_lib.erl snmpa_misc_sup.erl snmpa_mpd.erl snmpa_net_if.erl snmpa_net_if_filter.erl snmpa_set.erl snmpa_set_lib.erl snmpa_supervisor.erl snmpa_svbl.erl snmpa_symbolic_store.erl snmpa_target_cache.erl snmpa_trap.erl snmpa_usm.erl snmpa_vacm.erl snmp_community_mib.erl snmp_framework_mib.erl snmp_generic.erl snmp_generic_mnesia.erl snmp_index.erl snmp_notification_mib.erl snmp_shadow_table.erl snmp_standard_mib.erl snmp_target_mib.erl snmp_user_based_sm_mib.erl snmp_view_based_acm_mib.erl snmpa_vacm.hrl snmpa_atl.hrl snmpa_internal.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/agent"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmpa.beam ../../ebin/snmpa_authentication_service.beam ../../ebin/snmpa_discovery_handler.beam ../../ebin/snmpa_error_report.beam ../../ebin/snmpa_mib_storage.beam ../../ebin/snmpa_mib_data.beam ../../ebin/snmpa_network_interface.beam ../../ebin/snmpa_network_interface_filter.beam ../../ebin/snmpa_notification_delivery_info_receiver.beam ../../ebin/snmpa_notification_filter.beam ../../ebin/snmpa_set_mechanism.beam ../../ebin/snmpa_acm.beam ../../ebin/snmpa_agent.beam ../../ebin/snmpa_agent_sup.beam ../../ebin/snmpa_app.beam ../../ebin/snmpa_conf.beam ../../ebin/snmpa_discovery_handler_default.beam ../../ebin/snmpa_error.beam ../../ebin/snmpa_error_io.beam ../../ebin/snmpa_error_logger.beam ../../ebin/snmpa_local_db.beam ../../ebin/snmpa_mib_storage_ets.beam ../../ebin/snmpa_mib_storage_dets.beam ../../ebin/snmpa_mib_storage_mnesia.beam ../../ebin/snmpa_mib.beam ../../ebin/snmpa_mib_data_tttn.beam ../../ebin/snmpa_mib_lib.beam ../../ebin/snmpa_misc_sup.beam ../../ebin/snmpa_mpd.beam ../../ebin/snmpa_net_if.beam ../../ebin/snmpa_net_if_filter.beam ../../ebin/snmpa_set.beam ../../ebin/snmpa_set_lib.beam ../../ebin/snmpa_supervisor.beam ../../ebin/snmpa_svbl.beam ../../ebin/snmpa_symbolic_store.beam ../../ebin/snmpa_target_cache.beam ../../ebin/snmpa_trap.beam ../../ebin/snmpa_usm.beam ../../ebin/snmpa_vacm.beam ../../ebin/snmp_community_mib.beam ../../ebin/snmp_framework_mib.beam ../../ebin/snmp_generic.beam ../../ebin/snmp_generic_mnesia.beam ../../ebin/snmp_index.beam ../../ebin/snmp_notification_mib.beam ../../ebin/snmp_shadow_table.beam ../../ebin/snmp_standard_mib.beam ../../ebin/snmp_target_mib.beam ../../ebin/snmp_user_based_sm_mib.beam ../../ebin/snmp_view_based_acm_mib.beam   \
		"/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/src/manager"
/usr/bin/install -c -m 644 snmpm_user.erl snmpm_user_old.erl snmpm_network_interface.erl snmpm_network_interface_filter.erl snmpm.erl snmpm_conf.erl snmpm_config.erl snmpm_mpd.erl snmpm_misc_sup.erl snmpm_net_if.erl snmpm_net_if_mt.erl snmpm_net_if_filter.erl snmpm_server.erl snmpm_server_sup.erl snmpm_supervisor.erl snmpm_user_default.erl snmpm_usm.erl snmpm_usm.hrl snmpm_atl.hrl snmpm_internal.hrl "/usr/local/lib/erlang/lib/snmp-5.2.4/src/manager"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
/usr/bin/install -c -m 644 ../../ebin/snmpm_user.beam ../../ebin/snmpm_user_old.beam ../../ebin/snmpm_network_interface.beam ../../ebin/snmpm_network_interface_filter.beam ../../ebin/snmpm.beam ../../ebin/snmpm_conf.beam ../../ebin/snmpm_config.beam ../../ebin/snmpm_mpd.beam ../../ebin/snmpm_misc_sup.beam ../../ebin/snmpm_net_if.beam ../../ebin/snmpm_net_if_mt.beam ../../ebin/snmpm_net_if_filter.beam ../../ebin/snmpm_server.beam ../../ebin/snmpm_server_sup.beam ../../ebin/snmpm_supervisor.beam ../../ebin/snmpm_user_default.beam ../../ebin/snmpm_usm.beam "/usr/local/lib/erlang/lib/snmp-5.2.4/ebin"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex1
/usr/bin/install -c -m 644 EX1-MIB.funcs EX1-MIB.mib "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex1
/usr/bin/install -c -m 644 ex1.erl "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex1
/usr/bin/install -c -m 644 EX1-MIB.bin ex1.beam "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex1
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex1'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex2
/usr/bin/install -c -m 644 snmp_ex2_manager.erl snmp_ex2_simple_standard_test.erl "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex2
/usr/bin/install -c -m 644 snmp_ex2_manager.beam snmp_ex2_simple_standard_test.beam "/usr/local/lib/erlang/lib/snmp-5.2.4/examples"/ex2
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples/ex2'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf/agent"
/usr/bin/install -c -m 644 agent.conf community.conf context.conf notify.conf standard.conf target_addr.conf target_params.conf usm.conf vacm.conf "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf/agent"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/agent'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf/manager"
/usr/bin/install -c -m 644 manager.conf agents.conf users.conf "/usr/local/lib/erlang/lib/snmp-5.2.4/priv/conf/manager"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf/manager'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/priv/conf'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "snmp-5.2.4" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep snmp-5.2.4 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo snmp-5.2.4 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
=== Leaving application snmp
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/snmp'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
=== Entering application otp_mibs
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/src"
/usr/bin/install -c -m 644 otp_mib.erl "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/ebin"
/usr/bin/install -c -m 644 ../ebin/otp_mib.beam ../ebin/otp_mibs.app ../ebin/otp_mibs.appup "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/mibs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/mibs/v1"
/usr/bin/install -c -m 644 OTP-REG.mib OTP-TC.mib OTP-MIB.mib OTP-MIB.funcs "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/mibs"
/usr/bin/install -c -m 644 v1/OTP-REG.mib.v1 v1/OTP-TC.mib.v1 v1/OTP-MIB.mib.v1 "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/mibs/v1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/include"
/usr/bin/install -c -m 644 ../include/OTP-REG.hrl ../include/OTP-TC.hrl ../include/OTP-MIB.hrl "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/priv/mibs"
/usr/bin/install -c -m 644 ../priv/mibs/OTP-REG.bin ../priv/mibs/OTP-TC.bin ../priv/mibs/OTP-MIB.bin "/usr/local/lib/erlang/lib/otp_mibs-1.1.1/priv/mibs"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "otp_mibs-1.1.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep otp_mibs-1.1.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo otp_mibs-1.1.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
=== Leaving application otp_mibs
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
=== Entering application erl_interface
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/lib"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/auxdir"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/connect"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/decode"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/encode"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/epmd"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/legacy"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/misc"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/prog"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/registry"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/lib"
/usr/bin/install -c -m 644 ../ebin/erl_interface.app  "/usr/local/lib/erlang/lib/erl_interface-3.9.1/ebin/erl_interface.app"
/usr/bin/install -c -m 644 ../ebin/erl_interface.appup  "/usr/local/lib/erlang/lib/erl_interface-3.9.1/ebin/erl_interface.appup"
/usr/bin/install -c -m 644 ../include/ei.h ../include/ei_connect.h ../include/eicode.h ../include/erl_interface.h     "/usr/local/lib/erlang/lib/erl_interface-3.9.1/include"
/usr/bin/install -c -m 644 ../include/ei.h ../include/ei_connect.h ../include/eicode.h ../include/erl_interface.h     "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei_st.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface_st.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface.a "/usr/local/lib/erlang/lib/erl_interface-3.9.1/lib"
/usr/bin/install -c -m 644 /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei_st.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface_st.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei.a /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface.a "/usr/local/lib/erlang/usr/lib"
/usr/bin/install -c /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/bin/x86_64-unknown-linux-gnu/erl_call "/usr/local/lib/erlang/lib/erl_interface-3.9.1/bin"
/usr/bin/install -c -m 644 INSTALL Makefile Makefile.in README README.internal x86_64-unknown-linux-gnu/eidefs.mk        "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src"
/usr/bin/install -c -m 644 connect/*.[ch]  "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/connect"
/usr/bin/install -c -m 644 decode/*.[ch]   "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/decode"
/usr/bin/install -c -m 644 encode/*.[ch]   "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/encode"
/usr/bin/install -c -m 644 epmd/*.[ch]     "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/epmd"
/usr/bin/install -c -m 644 misc/*.[ch]     "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/misc"
/usr/bin/install -c -m 644 registry/*.[ch] "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/registry"
/usr/bin/install -c -m 644 legacy/*.[ch]   "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/legacy"
/usr/bin/install -c -m 644 prog/*.[ch]     "/usr/local/lib/erlang/lib/erl_interface-3.9.1/src/prog"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "erl_interface-3.9.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep erl_interface-3.9.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo erl_interface-3.9.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
=== Leaving application erl_interface
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
=== Entering application asn1
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/asn1-4.0.4/ebin"
/usr/bin/install -c -m 644 ../ebin/asn1ct.beam ../ebin/asn1ct_check.beam ../ebin/asn1_db.beam ../ebin/asn1ct_pretty_format.beam ../ebin/asn1ct_func.beam ../ebin/asn1ct_gen.beam ../ebin/asn1ct_gen_check.beam ../ebin/asn1ct_gen_per.beam ../ebin/asn1ct_name.beam ../ebin/asn1ct_constructed_per.beam ../ebin/asn1ct_constructed_ber_bin_v2.beam ../ebin/asn1ct_gen_ber_bin_v2.beam ../ebin/asn1ct_imm.beam ../ebin/asn1ct_rtt.beam ../ebin/asn1ct_value.beam ../ebin/asn1ct_tok.beam ../ebin/asn1ct_parser2.beam ../ebin/asn1ct_table.beam ../ebin/asn1ct_eval_ext.beam ../ebin/asn1rt.beam ../ebin/asn1rt_nif.beam ../ebin/asn1.app ../ebin/asn1.appup "/usr/local/lib/erlang/lib/asn1-4.0.4/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/asn1-4.0.4/src"
/usr/bin/install -c -m 644  asn1ct.erl asn1ct_check.erl asn1_db.erl asn1ct_pretty_format.erl asn1ct_func.erl asn1ct_gen.erl asn1ct_gen_check.erl asn1ct_gen_per.erl asn1ct_name.erl asn1ct_constructed_per.erl asn1ct_constructed_ber_bin_v2.erl asn1ct_gen_ber_bin_v2.erl asn1ct_imm.erl asn1ct_rtt.erl asn1ct_value.erl asn1ct_tok.erl asn1ct_parser2.erl asn1ct_table.erl asn1ct_eval_ext.erl asn1rt.erl asn1rt_nif.erl asn1_records.hrl asn1.app.src asn1.appup.src "/usr/local/lib/erlang/lib/asn1-4.0.4/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/asn1-4.0.4/examples"
/usr/bin/install -c -m 644 ../examples/P-Record.asn "/usr/local/lib/erlang/lib/asn1-4.0.4/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/asn1-4.0.4/priv/lib"
/usr/bin/install -c ../priv/lib/x86_64-unknown-linux-gnu/asn1rt_nif.so "/usr/local/lib/erlang/lib/asn1-4.0.4/priv/lib"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/asn1-4.0.4/c_src"
/usr/bin/install -c -m 644 *.c "/usr/local/lib/erlang/lib/asn1-4.0.4/c_src"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "asn1-4.0.4" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep asn1-4.0.4 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo asn1-4.0.4 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
=== Leaving application asn1
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
=== Entering application jinterface
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src/com/ericsson/otp/erlang'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "jinterface-1.7.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep jinterface-1.7.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo jinterface-1.7.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
=== Leaving application jinterface
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
=== Entering application wx
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/src"
/usr/bin/install -c -m 644 wxe.hrl        wx.erl wx_object.erl wxe_master.erl wxe_server.erl wxe_util.erl "/usr/local/lib/erlang/lib/wx-1.7.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/src/gen"
/usr/bin/install -c -m 644 gen/wxe_debug.hrl gen/wxe_funcs.hrl gen/wxAcceleratorEntry.erl gen/wxAcceleratorTable.erl gen/wxActivateEvent.erl gen/wxArtProvider.erl gen/wxAuiDockArt.erl gen/wxAuiManager.erl gen/wxAuiManagerEvent.erl gen/wxAuiNotebook.erl gen/wxAuiNotebookEvent.erl gen/wxAuiPaneInfo.erl gen/wxAuiSimpleTabArt.erl gen/wxAuiTabArt.erl gen/wxBitmapButton.erl gen/wxBitmapDataObject.erl gen/wxBitmap.erl gen/wxBoxSizer.erl gen/wxBrush.erl gen/wxBufferedDC.erl gen/wxBufferedPaintDC.erl gen/wxButton.erl gen/wxCalendarCtrl.erl gen/wxCalendarDateAttr.erl gen/wxCalendarEvent.erl gen/wxCaret.erl gen/wxCheckBox.erl gen/wxCheckListBox.erl gen/wxChildFocusEvent.erl gen/wxChoicebook.erl gen/wxChoice.erl gen/wxClientDC.erl gen/wxClipboard.erl gen/wxClipboardTextEvent.erl gen/wxCloseEvent.erl gen/wxColourData.erl gen/wxColourDialog.erl gen/wxColourPickerCtrl.erl gen/wxColourPickerEvent.erl gen/wxComboBox.erl gen/wxCommandEvent.erl gen/wxContextMenuEvent.erl gen/wxControl.erl gen/wxControlWithItems.erl gen/wxCursor.erl gen/wxDataObject.erl gen/wxDateEvent.erl gen/wxDatePickerCtrl.erl gen/wxDC.erl gen/wxDCOverlay.erl gen/wxDialog.erl gen/wxDirDialog.erl gen/wxDirPickerCtrl.erl gen/wxDisplayChangedEvent.erl gen/wxEraseEvent.erl gen/wxEvent.erl gen/wxEvtHandler.erl gen/wxFileDataObject.erl gen/wxFileDialog.erl gen/wxFileDirPickerEvent.erl gen/wxFilePickerCtrl.erl gen/wxFindReplaceData.erl gen/wxFindReplaceDialog.erl gen/wxFlexGridSizer.erl gen/wxFocusEvent.erl gen/wxFontData.erl gen/wxFontDialog.erl gen/wxFont.erl gen/wxFontPickerCtrl.erl gen/wxFontPickerEvent.erl gen/wxFrame.erl gen/wxGauge.erl gen/wxGBSizerItem.erl gen/wxGenericDirCtrl.erl gen/wxGLCanvas.erl gen/wxGraphicsBrush.erl gen/wxGraphicsContext.erl gen/wxGraphicsFont.erl gen/wxGraphicsMatrix.erl gen/wxGraphicsObject.erl gen/wxGraphicsPath.erl gen/wxGraphicsPen.erl gen/wxGraphicsRenderer.erl gen/wxGridBagSizer.erl gen/wxGridCellAttr.erl gen/wxGridCellBoolEditor.erl gen/wxGridCellBoolRenderer.erl gen/wxGridCellChoiceEditor.erl gen/wxGridCellEditor.erl gen/wxGridCellFloatEditor.erl gen/wxGridCellFloatRenderer.erl gen/wxGridCellNumberEditor.erl gen/wxGridCellNumberRenderer.erl gen/wxGridCellRenderer.erl gen/wxGridCellStringRenderer.erl gen/wxGridCellTextEditor.erl gen/wxGrid.erl gen/wxGridEvent.erl gen/wxGridSizer.erl gen/wxHelpEvent.erl gen/wxHtmlEasyPrinting.erl gen/wxHtmlLinkEvent.erl gen/wxHtmlWindow.erl gen/wxIconBundle.erl gen/wxIcon.erl gen/wxIconizeEvent.erl gen/wxIdleEvent.erl gen/wxImage.erl gen/wxImageList.erl gen/wxInitDialogEvent.erl gen/wxJoystickEvent.erl gen/wxKeyEvent.erl gen/wxLayoutAlgorithm.erl gen/wxListbook.erl gen/wxListBox.erl gen/wxListCtrl.erl gen/wxListEvent.erl gen/wxListItemAttr.erl gen/wxListItem.erl gen/wxListView.erl gen/wxLocale.erl gen/wxLogNull.erl gen/wxMask.erl gen/wxMaximizeEvent.erl gen/wxMDIChildFrame.erl gen/wxMDIClientWindow.erl gen/wxMDIParentFrame.erl gen/wxMemoryDC.erl gen/wxMenuBar.erl gen/wxMenu.erl gen/wxMenuEvent.erl gen/wxMenuItem.erl gen/wxMessageDialog.erl gen/wxMiniFrame.erl gen/wxMirrorDC.erl gen/wx_misc.erl gen/wxMouseCaptureChangedEvent.erl gen/wxMouseCaptureLostEvent.erl gen/wxMouseEvent.erl gen/wxMoveEvent.erl gen/wxMultiChoiceDialog.erl gen/wxNavigationKeyEvent.erl gen/wxNotebook.erl gen/wxNotebookEvent.erl gen/wxNotifyEvent.erl gen/wxOverlay.erl gen/wxPageSetupDialogData.erl gen/wxPageSetupDialog.erl gen/wxPaintDC.erl gen/wxPaintEvent.erl gen/wxPaletteChangedEvent.erl gen/wxPalette.erl gen/wxPanel.erl gen/wxPasswordEntryDialog.erl gen/wxPen.erl gen/wxPickerBase.erl gen/wxPopupTransientWindow.erl gen/wxPopupWindow.erl gen/wxPostScriptDC.erl gen/wxPreviewCanvas.erl gen/wxPreviewControlBar.erl gen/wxPreviewFrame.erl gen/wxPrintData.erl gen/wxPrintDialogData.erl gen/wxPrintDialog.erl gen/wxPrinter.erl gen/wxPrintout.erl gen/wxPrintPreview.erl gen/wxProgressDialog.erl gen/wxQueryNewPaletteEvent.erl gen/wxRadioBox.erl gen/wxRadioButton.erl gen/wxRegion.erl gen/wxSashEvent.erl gen/wxSashLayoutWindow.erl gen/wxSashWindow.erl gen/wxScreenDC.erl gen/wxScrollBar.erl gen/wxScrolledWindow.erl gen/wxScrollEvent.erl gen/wxScrollWinEvent.erl gen/wxSetCursorEvent.erl gen/wxShowEvent.erl gen/wxSingleChoiceDialog.erl gen/wxSizeEvent.erl gen/wxSizer.erl gen/wxSizerFlags.erl gen/wxSizerItem.erl gen/wxSlider.erl gen/wxSpinButton.erl gen/wxSpinCtrl.erl gen/wxSpinEvent.erl gen/wxSplashScreen.erl gen/wxSplitterEvent.erl gen/wxSplitterWindow.erl gen/wxStaticBitmap.erl gen/wxStaticBox.erl gen/wxStaticBoxSizer.erl gen/wxStaticLine.erl gen/wxStaticText.erl gen/wxStatusBar.erl gen/wxStdDialogButtonSizer.erl gen/wxStyledTextCtrl.erl gen/wxStyledTextEvent.erl gen/wxSysColourChangedEvent.erl gen/wxSystemOptions.erl gen/wxSystemSettings.erl gen/wxTaskBarIcon.erl gen/wxTaskBarIconEvent.erl gen/wxTextAttr.erl gen/wxTextCtrl.erl gen/wxTextDataObject.erl gen/wxTextEntryDialog.erl gen/wxToggleButton.erl gen/wxToolBar.erl gen/wxToolbook.erl gen/wxToolTip.erl gen/wxTopLevelWindow.erl gen/wxTreebook.erl gen/wxTreeCtrl.erl gen/wxTreeEvent.erl gen/wxUpdateUIEvent.erl gen/wxWindowCreateEvent.erl gen/wxWindowDC.erl gen/wxWindowDestroyEvent.erl gen/wxWindow.erl gen/wxXmlResource.erl gen/glu.erl gen/gl.erl "/usr/local/lib/erlang/lib/wx-1.7.1/src/gen"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/include"
/usr/bin/install -c -m 644 ../include/wx.hrl ../include/gl.hrl ../include/glu.hrl "/usr/local/lib/erlang/lib/wx-1.7.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/ebin"
/usr/bin/install -c -m 644 ../ebin/wx.beam ../ebin/wx_object.beam ../ebin/wxe_master.beam ../ebin/wxe_server.beam ../ebin/wxe_util.beam ../ebin/wxAcceleratorEntry.beam ../ebin/wxAcceleratorTable.beam ../ebin/wxActivateEvent.beam ../ebin/wxArtProvider.beam ../ebin/wxAuiDockArt.beam ../ebin/wxAuiManager.beam ../ebin/wxAuiManagerEvent.beam ../ebin/wxAuiNotebook.beam ../ebin/wxAuiNotebookEvent.beam ../ebin/wxAuiPaneInfo.beam ../ebin/wxAuiSimpleTabArt.beam ../ebin/wxAuiTabArt.beam ../ebin/wxBitmapButton.beam ../ebin/wxBitmapDataObject.beam ../ebin/wxBitmap.beam ../ebin/wxBoxSizer.beam ../ebin/wxBrush.beam ../ebin/wxBufferedDC.beam ../ebin/wxBufferedPaintDC.beam ../ebin/wxButton.beam ../ebin/wxCalendarCtrl.beam ../ebin/wxCalendarDateAttr.beam ../ebin/wxCalendarEvent.beam ../ebin/wxCaret.beam ../ebin/wxCheckBox.beam ../ebin/wxCheckListBox.beam ../ebin/wxChildFocusEvent.beam ../ebin/wxChoicebook.beam ../ebin/wxChoice.beam ../ebin/wxClientDC.beam ../ebin/wxClipboard.beam ../ebin/wxClipboardTextEvent.beam ../ebin/wxCloseEvent.beam ../ebin/wxColourData.beam ../ebin/wxColourDialog.beam ../ebin/wxColourPickerCtrl.beam ../ebin/wxColourPickerEvent.beam ../ebin/wxComboBox.beam ../ebin/wxCommandEvent.beam ../ebin/wxContextMenuEvent.beam ../ebin/wxControl.beam ../ebin/wxControlWithItems.beam ../ebin/wxCursor.beam ../ebin/wxDataObject.beam ../ebin/wxDateEvent.beam ../ebin/wxDatePickerCtrl.beam ../ebin/wxDC.beam ../ebin/wxDCOverlay.beam ../ebin/wxDialog.beam ../ebin/wxDirDialog.beam ../ebin/wxDirPickerCtrl.beam ../ebin/wxDisplayChangedEvent.beam ../ebin/wxEraseEvent.beam ../ebin/wxEvent.beam ../ebin/wxEvtHandler.beam ../ebin/wxFileDataObject.beam ../ebin/wxFileDialog.beam ../ebin/wxFileDirPickerEvent.beam ../ebin/wxFilePickerCtrl.beam ../ebin/wxFindReplaceData.beam ../ebin/wxFindReplaceDialog.beam ../ebin/wxFlexGridSizer.beam ../ebin/wxFocusEvent.beam ../ebin/wxFontData.beam ../ebin/wxFontDialog.beam ../ebin/wxFont.beam ../ebin/wxFontPickerCtrl.beam ../ebin/wxFontPickerEvent.beam ../ebin/wxFrame.beam ../ebin/wxGauge.beam ../ebin/wxGBSizerItem.beam ../ebin/wxGenericDirCtrl.beam ../ebin/wxGLCanvas.beam ../ebin/wxGraphicsBrush.beam ../ebin/wxGraphicsContext.beam ../ebin/wxGraphicsFont.beam ../ebin/wxGraphicsMatrix.beam ../ebin/wxGraphicsObject.beam ../ebin/wxGraphicsPath.beam ../ebin/wxGraphicsPen.beam ../ebin/wxGraphicsRenderer.beam ../ebin/wxGridBagSizer.beam ../ebin/wxGridCellAttr.beam ../ebin/wxGridCellBoolEditor.beam ../ebin/wxGridCellBoolRenderer.beam ../ebin/wxGridCellChoiceEditor.beam ../ebin/wxGridCellEditor.beam ../ebin/wxGridCellFloatEditor.beam ../ebin/wxGridCellFloatRenderer.beam ../ebin/wxGridCellNumberEditor.beam ../ebin/wxGridCellNumberRenderer.beam ../ebin/wxGridCellRenderer.beam ../ebin/wxGridCellStringRenderer.beam ../ebin/wxGridCellTextEditor.beam ../ebin/wxGrid.beam ../ebin/wxGridEvent.beam ../ebin/wxGridSizer.beam ../ebin/wxHelpEvent.beam ../ebin/wxHtmlEasyPrinting.beam ../ebin/wxHtmlLinkEvent.beam ../ebin/wxHtmlWindow.beam ../ebin/wxIconBundle.beam ../ebin/wxIcon.beam ../ebin/wxIconizeEvent.beam ../ebin/wxIdleEvent.beam ../ebin/wxImage.beam ../ebin/wxImageList.beam ../ebin/wxInitDialogEvent.beam ../ebin/wxJoystickEvent.beam ../ebin/wxKeyEvent.beam ../ebin/wxLayoutAlgorithm.beam ../ebin/wxListbook.beam ../ebin/wxListBox.beam ../ebin/wxListCtrl.beam ../ebin/wxListEvent.beam ../ebin/wxListItemAttr.beam ../ebin/wxListItem.beam ../ebin/wxListView.beam ../ebin/wxLocale.beam ../ebin/wxLogNull.beam ../ebin/wxMask.beam ../ebin/wxMaximizeEvent.beam ../ebin/wxMDIChildFrame.beam ../ebin/wxMDIClientWindow.beam ../ebin/wxMDIParentFrame.beam ../ebin/wxMemoryDC.beam ../ebin/wxMenuBar.beam ../ebin/wxMenu.beam ../ebin/wxMenuEvent.beam ../ebin/wxMenuItem.beam ../ebin/wxMessageDialog.beam ../ebin/wxMiniFrame.beam ../ebin/wxMirrorDC.beam ../ebin/wx_misc.beam ../ebin/wxMouseCaptureChangedEvent.beam ../ebin/wxMouseCaptureLostEvent.beam ../ebin/wxMouseEvent.beam ../ebin/wxMoveEvent.beam ../ebin/wxMultiChoiceDialog.beam ../ebin/wxNavigationKeyEvent.beam ../ebin/wxNotebook.beam ../ebin/wxNotebookEvent.beam ../ebin/wxNotifyEvent.beam ../ebin/wxOverlay.beam ../ebin/wxPageSetupDialogData.beam ../ebin/wxPageSetupDialog.beam ../ebin/wxPaintDC.beam ../ebin/wxPaintEvent.beam ../ebin/wxPaletteChangedEvent.beam ../ebin/wxPalette.beam ../ebin/wxPanel.beam ../ebin/wxPasswordEntryDialog.beam ../ebin/wxPen.beam ../ebin/wxPickerBase.beam ../ebin/wxPopupTransientWindow.beam ../ebin/wxPopupWindow.beam ../ebin/wxPostScriptDC.beam ../ebin/wxPreviewCanvas.beam ../ebin/wxPreviewControlBar.beam ../ebin/wxPreviewFrame.beam ../ebin/wxPrintData.beam ../ebin/wxPrintDialogData.beam ../ebin/wxPrintDialog.beam ../ebin/wxPrinter.beam ../ebin/wxPrintout.beam ../ebin/wxPrintPreview.beam ../ebin/wxProgressDialog.beam ../ebin/wxQueryNewPaletteEvent.beam ../ebin/wxRadioBox.beam ../ebin/wxRadioButton.beam ../ebin/wxRegion.beam ../ebin/wxSashEvent.beam ../ebin/wxSashLayoutWindow.beam ../ebin/wxSashWindow.beam ../ebin/wxScreenDC.beam ../ebin/wxScrollBar.beam ../ebin/wxScrolledWindow.beam ../ebin/wxScrollEvent.beam ../ebin/wxScrollWinEvent.beam ../ebin/wxSetCursorEvent.beam ../ebin/wxShowEvent.beam ../ebin/wxSingleChoiceDialog.beam ../ebin/wxSizeEvent.beam ../ebin/wxSizer.beam ../ebin/wxSizerFlags.beam ../ebin/wxSizerItem.beam ../ebin/wxSlider.beam ../ebin/wxSpinButton.beam ../ebin/wxSpinCtrl.beam ../ebin/wxSpinEvent.beam ../ebin/wxSplashScreen.beam ../ebin/wxSplitterEvent.beam ../ebin/wxSplitterWindow.beam ../ebin/wxStaticBitmap.beam ../ebin/wxStaticBox.beam ../ebin/wxStaticBoxSizer.beam ../ebin/wxStaticLine.beam ../ebin/wxStaticText.beam ../ebin/wxStatusBar.beam ../ebin/wxStdDialogButtonSizer.beam ../ebin/wxStyledTextCtrl.beam ../ebin/wxStyledTextEvent.beam ../ebin/wxSysColourChangedEvent.beam ../ebin/wxSystemOptions.beam ../ebin/wxSystemSettings.beam ../ebin/wxTaskBarIcon.beam ../ebin/wxTaskBarIconEvent.beam ../ebin/wxTextAttr.beam ../ebin/wxTextCtrl.beam ../ebin/wxTextDataObject.beam ../ebin/wxTextEntryDialog.beam ../ebin/wxToggleButton.beam ../ebin/wxToolBar.beam ../ebin/wxToolbook.beam ../ebin/wxToolTip.beam ../ebin/wxTopLevelWindow.beam ../ebin/wxTreebook.beam ../ebin/wxTreeCtrl.beam ../ebin/wxTreeEvent.beam ../ebin/wxUpdateUIEvent.beam ../ebin/wxWindowCreateEvent.beam ../ebin/wxWindowDC.beam ../ebin/wxWindowDestroyEvent.beam ../ebin/wxWindow.beam ../ebin/wxXmlResource.beam ../ebin/glu.beam ../ebin/gl.beam  "/usr/local/lib/erlang/lib/wx-1.7.1/ebin"
/usr/bin/install -c -m 644 ../ebin/wx.app ../ebin/wx.appup "/usr/local/lib/erlang/lib/wx-1.7.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/examples/demo"
/usr/bin/install -c -m 644 demo.erl demo_html_tagger.erl ex_aui.erl ex_button.erl ex_canvas.erl ex_canvas_paint.erl ex_choices.erl ex_cursor.erl ex_dialogs.erl ex_frame_utils.erl ex_gauge.erl ex_gl.erl ex_grid.erl ex_htmlWindow.erl ex_listCtrl.erl ex_notebook.erl ex_pickers.erl ex_popupMenu.erl ex_radioBox.erl ex_sashWindow.erl ex_sizers.erl ex_slider.erl ex_splitterWindow.erl ex_static.erl ex_textCtrl.erl ex_treeCtrl.erl ex_graphicsContext.erl  "/usr/local/lib/erlang/lib/wx-1.7.1/examples/demo"
/usr/bin/install -c -m 644 demo.beam demo_html_tagger.beam ex_aui.beam ex_button.beam ex_canvas.beam ex_canvas_paint.beam ex_choices.beam ex_cursor.beam ex_dialogs.beam ex_frame_utils.beam ex_gauge.beam ex_gl.beam ex_grid.beam ex_htmlWindow.beam ex_listCtrl.beam ex_notebook.beam ex_pickers.beam ex_popupMenu.beam ex_radioBox.beam ex_sashWindow.beam ex_sizers.beam ex_slider.beam ex_splitterWindow.beam ex_static.beam ex_textCtrl.beam ex_treeCtrl.beam ex_graphicsContext.beam "/usr/local/lib/erlang/lib/wx-1.7.1/examples/demo"
/usr/bin/install -c -m 644 image.jpg erlang.png ex_htmlWindow.html "/usr/local/lib/erlang/lib/wx-1.7.1/examples/demo"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/examples/sudoku"
/usr/bin/install -c -m 644 sudoku.erl sudoku_board.erl sudoku_game.erl sudoku_gui.erl sudoku.hrl "/usr/local/lib/erlang/lib/wx-1.7.1/examples/sudoku"
/usr/bin/install -c -m 644 sudoku.beam sudoku_board.beam sudoku_game.beam sudoku_gui.beam "/usr/local/lib/erlang/lib/wx-1.7.1/examples/sudoku"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/examples/simple"
/usr/bin/install -c -m 644 hello.erl hello2.erl minimal.erl menu.erl "/usr/local/lib/erlang/lib/wx-1.7.1/examples/simple"
/usr/bin/install -c -m 644 copy.xpm sample.xpm hello.beam hello2.beam minimal.beam menu.beam "/usr/local/lib/erlang/lib/wx-1.7.1/examples/simple"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/examples/xrc"
/usr/bin/install -c -m 644 xrc.erl "/usr/local/lib/erlang/lib/wx-1.7.1/examples/xrc"
/usr/bin/install -c -m 644 xrc.beam "/usr/local/lib/erlang/lib/wx-1.7.1/examples/xrc"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/wx-1.7.1/examples/xrc"/rc
/usr/bin/install -c -m 644 rc/appicon.ico rc/basicdlg.xpm rc/custclas.xpm rc/fileopen.gif rc/menu.xrc rc/resource.xrc rc/uncenter.xpm rc/variable.xrc rc/appicon.xpm rc/basicdlg.xrc rc/custclas.xrc rc/filesave.gif rc/platform.xpm rc/stop.xpm rc/uncenter.xrc rc/artprov.xpm rc/controls.xpm rc/derivdlg.xpm rc/frame.xrc rc/platform.xrc rc/throbber.gif rc/update.gif rc/artprov.xrc rc/controls.xrc rc/derivdlg.xrc rc/fuzzy.gif rc/quotes.gif rc/toolbar.xrc rc/variable.xpm "/usr/local/lib/erlang/lib/wx-1.7.1/examples/xrc"/rc
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "wx-1.7.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep wx-1.7.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo wx-1.7.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
=== Leaving application wx
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
=== Entering application debugger
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/debugger-4.2.1/src"
/usr/bin/install -c -m 644 debugger.erl i.erl int.erl dbg_debugged.erl dbg_icmd.erl dbg_idb.erl dbg_ieval.erl dbg_iload.erl dbg_iserver.erl dbg_istk.erl dbg_wx_break.erl dbg_wx_break_win.erl dbg_wx_code.erl dbg_wx_filedialog_win.erl dbg_wx_interpret.erl dbg_wx_mon.erl dbg_wx_mon_win.erl dbg_wx_settings.erl dbg_wx_src_view.erl dbg_wx_trace.erl dbg_wx_trace_win.erl dbg_wx_view.erl dbg_wx_win.erl dbg_wx_winman.erl dbg_ieval.hrl dbg_wx_filedialog_win.hrl  "/usr/local/lib/erlang/lib/debugger-4.2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/debugger-4.2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/debugger.beam ../ebin/i.beam ../ebin/int.beam ../ebin/dbg_debugged.beam ../ebin/dbg_icmd.beam ../ebin/dbg_idb.beam ../ebin/dbg_ieval.beam ../ebin/dbg_iload.beam ../ebin/dbg_iserver.beam ../ebin/dbg_istk.beam ../ebin/dbg_wx_break.beam ../ebin/dbg_wx_break_win.beam ../ebin/dbg_wx_code.beam ../ebin/dbg_wx_filedialog_win.beam ../ebin/dbg_wx_interpret.beam ../ebin/dbg_wx_mon.beam ../ebin/dbg_wx_mon_win.beam ../ebin/dbg_wx_settings.beam ../ebin/dbg_wx_src_view.beam ../ebin/dbg_wx_trace.beam ../ebin/dbg_wx_trace_win.beam ../ebin/dbg_wx_view.beam ../ebin/dbg_wx_win.beam ../ebin/dbg_wx_winman.beam ../ebin/debugger.app ../ebin/debugger.appup  "/usr/local/lib/erlang/lib/debugger-4.2.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/debugger-4.2.1/priv"
/usr/bin/install -c -m 644 debugger.tool debugger.gif erlang_bug.png  "/usr/local/lib/erlang/lib/debugger-4.2.1/priv"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "debugger-4.2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep debugger-4.2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo debugger-4.2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
=== Leaving application debugger
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
=== Entering application reltool
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/reltool-0.7.2/src"
/usr/bin/install -c -m 644 reltool.hrl reltool_fgraph.hrl reltool.erl reltool_app_win.erl reltool_fgraph.erl reltool_fgraph_win.erl reltool_mod_win.erl reltool_sys_win.erl reltool_server.erl reltool_target.erl reltool_utils.erl "/usr/local/lib/erlang/lib/reltool-0.7.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/reltool-0.7.2/ebin"
/usr/bin/install -c -m 644 ../ebin/reltool.beam ../ebin/reltool_app_win.beam ../ebin/reltool_fgraph.beam ../ebin/reltool_fgraph_win.beam ../ebin/reltool_mod_win.beam ../ebin/reltool_sys_win.beam ../ebin/reltool_server.beam ../ebin/reltool_target.beam ../ebin/reltool_utils.beam "/usr/local/lib/erlang/lib/reltool-0.7.2/ebin"
/usr/bin/install -c -m 644 ../ebin/reltool.app ../ebin/reltool.appup "/usr/local/lib/erlang/lib/reltool-0.7.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/reltool-0.7.2/examples"
/usr/bin/install -c -m 644  display_args mnesia_core_dump_viewer  "/usr/local/lib/erlang/lib/reltool-0.7.2/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "reltool-0.7.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep reltool-0.7.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo reltool-0.7.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
=== Leaving application reltool
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
=== Entering application gs
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/src"
/usr/bin/install -c -m 644 gs.app.src gs.erl gs_frontend.erl gs_make.erl gs_widgets.erl gstk.erl gstk_arc.erl gstk_button.erl gstk_canvas.erl gstk_checkbutton.erl gstk_db.erl gstk_editor.erl gstk_entry.erl gstk_font.erl gstk_frame.erl gstk_grid.erl gstk_gridline.erl gs_packer.erl gstk_gs.erl gstk_image.erl gstk_label.erl gstk_line.erl gstk_listbox.erl gstk_menu.erl gstk_menubar.erl gstk_menubutton.erl gstk_menuitem.erl gstk_oval.erl gstk_polygon.erl gstk_port_handler.erl gstk_radiobutton.erl gstk_rectangle.erl gstk_scale.erl gstk_text.erl gstk_widgets.erl gstk_window.erl tcl2erl.erl tool_utils.erl tool_file_dialog.erl gse.erl gstk.hrl gstk_generic.hrl \
		gstk_generic.erl "/usr/local/lib/erlang/lib/gs-1.6.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/ebin"
/usr/bin/install -c -m 644 ../ebin/gs.beam ../ebin/gs_frontend.beam ../ebin/gs_make.beam ../ebin/gs_widgets.beam ../ebin/gstk.beam ../ebin/gstk_arc.beam ../ebin/gstk_button.beam ../ebin/gstk_canvas.beam ../ebin/gstk_checkbutton.beam ../ebin/gstk_db.beam ../ebin/gstk_editor.beam ../ebin/gstk_entry.beam ../ebin/gstk_font.beam ../ebin/gstk_frame.beam ../ebin/gstk_grid.beam ../ebin/gstk_gridline.beam ../ebin/gs_packer.beam ../ebin/gstk_gs.beam ../ebin/gstk_image.beam ../ebin/gstk_label.beam ../ebin/gstk_line.beam ../ebin/gstk_listbox.beam ../ebin/gstk_menu.beam ../ebin/gstk_menubar.beam ../ebin/gstk_menubutton.beam ../ebin/gstk_menuitem.beam ../ebin/gstk_oval.beam ../ebin/gstk_polygon.beam ../ebin/gstk_port_handler.beam ../ebin/gstk_radiobutton.beam ../ebin/gstk_rectangle.beam ../ebin/gstk_scale.beam ../ebin/gstk_text.beam ../ebin/gstk_widgets.beam ../ebin/gstk_window.beam ../ebin/tcl2erl.beam ../ebin/tool_utils.beam ../ebin/tool_file_dialog.beam ../ebin/gse.beam gstk_generic.hrl ../ebin/gstk_generic.beam ../ebin/gs.app ../ebin/gs.appup "/usr/local/lib/erlang/lib/gs-1.6.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/priv/bitmap"
/usr/bin/install -c -m 644 ../priv/bitmap/fup.bm "/usr/local/lib/erlang/lib/gs-1.6.2/priv/bitmap"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/priv"
/usr/bin/install -c -m 644 ../priv/gstk.tcl ../priv/gs-xdefaults "/usr/local/lib/erlang/lib/gs-1.6.2/priv"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/examples/ebin"
/usr/bin/install -c -m 644 ../ebin/ball.beam ../ebin/browser.beam ../ebin/calc.beam ../ebin/calc2.beam ../ebin/color_demo.beam ../ebin/color_demo2.beam ../ebin/distrib_draw.beam ../ebin/entry_demo.beam ../ebin/event_test.beam ../ebin/file_dialog.beam ../ebin/focus_demo.beam ../ebin/frac.beam ../ebin/line_demo.beam ../ebin/man.beam ../ebin/menu_demo.beam ../ebin/rubber.beam "/usr/local/lib/erlang/lib/gs-1.6.2/examples/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/gs-1.6.2/examples/src"
/usr/bin/install -c -m 644 ball.erl browser.erl calc.erl calc2.erl color_demo.erl color_demo2.erl distrib_draw.erl entry_demo.erl event_test.erl file_dialog.erl focus_demo.erl frac.erl line_demo.erl man.erl menu_demo.erl rubber.erl  "/usr/local/lib/erlang/lib/gs-1.6.2/examples/src"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "gs-1.6.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep gs-1.6.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo gs-1.6.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
=== Leaving application gs
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
=== Entering application ic
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/ebin"
/usr/bin/install -c -m 644 ../ebin/ic.beam ../ebin/ic_erlbe.beam ../ebin/ic_cbe.beam ../ebin/icscan.beam ../ebin/icparse.beam ../ebin/iceval.beam ../ebin/ictype.beam ../ebin/ictk.beam ../ebin/icstruct.beam ../ebin/icenum.beam ../ebin/icpreproc.beam ../ebin/icunion.beam ../ebin/ic_pp.beam ../ebin/ic_pragma.beam ../ebin/ic_noc.beam ../ebin/ic_plainbe.beam ../ebin/ic_cclient.beam ../ebin/ic_cserver.beam ../ebin/ic_fetch.beam ../ebin/ic_code.beam ../ebin/ic_codegen.beam ../ebin/ic_error.beam ../ebin/ic_file.beam ../ebin/ic_forms.beam ../ebin/ic_genobj.beam ../ebin/ic_options.beam ../ebin/ic_symtab.beam ../ebin/ic_util.beam ../ebin/ic_jbe.beam ../ebin/ic_struct_java.beam ../ebin/ic_union_java.beam ../ebin/ic_enum_java.beam ../ebin/ic_constant_java.beam ../ebin/ic_sequence_java.beam ../ebin/ic_array_java.beam ../ebin/ic_attribute_java.beam ../ebin/ic_java_type.beam ../ebin/ic_erl_template.beam ../ebin/ic.app "/usr/local/lib/erlang/lib/ic-4.4.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/src"
/usr/bin/install -c -m 644 ic.erl ic_erlbe.erl ic_cbe.erl icscan.erl icparse.erl iceval.erl ictype.erl ictk.erl icstruct.erl icenum.erl icpreproc.erl icunion.erl ic_pp.erl ic_pragma.erl ic_noc.erl ic_plainbe.erl ic_cclient.erl ic_cserver.erl ic_fetch.erl ic_code.erl ic_codegen.erl ic_error.erl ic_file.erl ic_forms.erl ic_genobj.erl ic_options.erl ic_symtab.erl ic_util.erl ic_jbe.erl ic_struct_java.erl ic_union_java.erl ic_enum_java.erl ic_constant_java.erl ic_sequence_java.erl ic_array_java.erl ic_attribute_java.erl ic_java_type.erl ic_erl_template.erl	 icparse.yrl ic.hrl ic_debug.hrl icforms.hrl "/usr/local/lib/erlang/lib/ic-4.4.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/c-client"
/usr/bin/install -c -m 644 ../examples/c-client/ReadMe ../examples/c-client/Makefile ../examples/c-client/client.c ../examples/c-client/random.idl ../examples/c-client/rmod_random_impl.erl ../examples/c-client/test.erl "/usr/local/lib/erlang/lib/ic-4.4.2/examples/c-client"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/c-server"
/usr/bin/install -c -m 644 ../examples/c-server/ReadMe ../examples/c-server/Makefile ../examples/c-server/client.c ../examples/c-server/client.erl ../examples/c-server/server.c ../examples/c-server/callbacks.c ../examples/c-server/random.idl         "/usr/local/lib/erlang/lib/ic-4.4.2/examples/c-server"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/erl-plain"
/usr/bin/install -c -m 644 ../examples/erl-plain/ReadMe ../examples/erl-plain/rmod_random_impl.erl ../examples/erl-plain/random.idl "/usr/local/lib/erlang/lib/ic-4.4.2/examples/erl-plain"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/erl-genserv"
/usr/bin/install -c -m 644 ../examples/erl-genserv/ReadMe ../examples/erl-genserv/rmod_random_impl.erl ../examples/erl-genserv/random.idl "/usr/local/lib/erlang/lib/ic-4.4.2/examples/erl-genserv"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/java-client-server"
/usr/bin/install -c -m 644 ../examples/java-client-server/ReadMe ../examples/java-client-server/client.java ../examples/java-client-server/server.java ../examples/java-client-server/serverImpl.java ../examples/java-client-server/random.idl  "/usr/local/lib/erlang/lib/ic-4.4.2/examples/java-client-server"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/all-against-all"
/usr/bin/install -c -m 644 ../examples/all-against-all/ReadMe ../examples/all-against-all/Makefile ../examples/all-against-all/client.erl ../examples/all-against-all/server.erl ../examples/all-against-all/client.c ../examples/all-against-all/server.c ../examples/all-against-all/callbacks.c ../examples/all-against-all/client.java ../examples/all-against-all/server.java ../examples/all-against-all/serverImpl.java ../examples/all-against-all/random.idl  "/usr/local/lib/erlang/lib/ic-4.4.2/examples/all-against-all"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/c_src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/priv/lib"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/usr/lib"
/usr/bin/install -c -m 644 ic.c ic_tmo.c "/usr/local/lib/erlang/lib/ic-4.4.2/c_src"
/usr/bin/install -c -m 644 ../include/erlang.idl ../include/ic.h "/usr/local/lib/erlang/lib/ic-4.4.2/include"
/usr/bin/install -c -m 644 ../priv/lib/x86_64-unknown-linux-gnu/libic.a "/usr/local/lib/erlang/lib/ic-4.4.2/priv/lib"
/usr/bin/install -c -m 644 ../include/erlang.idl ../include/ic.h "/usr/local/lib/erlang/usr/include"
/usr/bin/install -c -m 644 ../priv/lib/x86_64-unknown-linux-gnu/libic.a "/usr/local/lib/erlang/usr/lib"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/java_src/com/ericsson/otp/ic"
/usr/bin/install -c -m 644 Holder.java BooleanHolder.java ByteHolder.java CharHolder.java DoubleHolder.java FloatHolder.java IntHolder.java LongHolder.java ShortHolder.java StringHolder.java Environment.java Any.java AnyHelper.java AnyHolder.java TypeCode.java TCKind.java Pid.java PidHolder.java PidHelper.java Ref.java RefHolder.java RefHelper.java Port.java PortHolder.java PortHelper.java Term.java TermHolder.java TermHelper.java "/usr/local/lib/erlang/lib/ic-4.4.2/java_src/com/ericsson/otp/ic"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/priv"
/usr/bin/install -c -m 644 /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/ic.jar "/usr/local/lib/erlang/lib/ic-4.4.2/priv"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ic-4.4.2/examples/pre_post_condition"
/usr/bin/install -c -m 644 m_i_impl.erl tracer.erl ex.idl  ReadMe.txt "/usr/local/lib/erlang/lib/ic-4.4.2/examples/pre_post_condition"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/examples/pre_post_condition'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "ic-4.4.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep ic-4.4.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo ic-4.4.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
=== Leaving application ic
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
=== Entering application mnesia
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/mnesia-4.14.1/src"
/usr/bin/install -c -m 644 mnesia.hrl mnesia.erl mnesia_backend_type.erl mnesia_backup.erl mnesia_bup.erl mnesia_checkpoint.erl mnesia_checkpoint_sup.erl mnesia_controller.erl mnesia_dumper.erl mnesia_event.erl mnesia_ext_sup.erl mnesia_frag.erl mnesia_frag_hash.erl mnesia_frag_old_hash.erl mnesia_index.erl mnesia_kernel_sup.erl mnesia_late_loader.erl mnesia_lib.erl mnesia_loader.erl mnesia_locker.erl mnesia_log.erl mnesia_monitor.erl mnesia_recover.erl mnesia_registry.erl mnesia_schema.erl mnesia_snmp_hook.erl mnesia_snmp_sup.erl mnesia_subscr.erl mnesia_sup.erl mnesia_sp.erl mnesia_text.erl mnesia_tm.erl "/usr/local/lib/erlang/lib/mnesia-4.14.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/mnesia-4.14.1/ebin"
/usr/bin/install -c -m 644 ../ebin/mnesia.beam ../ebin/mnesia_backend_type.beam ../ebin/mnesia_backup.beam ../ebin/mnesia_bup.beam ../ebin/mnesia_checkpoint.beam ../ebin/mnesia_checkpoint_sup.beam ../ebin/mnesia_controller.beam ../ebin/mnesia_dumper.beam ../ebin/mnesia_event.beam ../ebin/mnesia_ext_sup.beam ../ebin/mnesia_frag.beam ../ebin/mnesia_frag_hash.beam ../ebin/mnesia_frag_old_hash.beam ../ebin/mnesia_index.beam ../ebin/mnesia_kernel_sup.beam ../ebin/mnesia_late_loader.beam ../ebin/mnesia_lib.beam ../ebin/mnesia_loader.beam ../ebin/mnesia_locker.beam ../ebin/mnesia_log.beam ../ebin/mnesia_monitor.beam ../ebin/mnesia_recover.beam ../ebin/mnesia_registry.beam ../ebin/mnesia_schema.beam ../ebin/mnesia_snmp_hook.beam ../ebin/mnesia_snmp_sup.beam ../ebin/mnesia_subscr.beam ../ebin/mnesia_sup.beam ../ebin/mnesia_sp.beam ../ebin/mnesia_text.beam ../ebin/mnesia_tm.beam ../ebin/mnesia.app ../ebin/mnesia.appup "/usr/local/lib/erlang/lib/mnesia-4.14.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/mnesia-4.14.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/mnesia-4.14.1/examples"
/usr/bin/install -c -m 644 company.erl company_o.erl bup.erl mnesia_meter.erl mnesia_tpcb.erl DATA company.hrl company_o.hrl "/usr/local/lib/erlang/lib/mnesia-4.14.1/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/mnesia-4.14.1/examples/bench"
(cd bench; /usr/bin/install -c -m 644 \
          Makefile \
          README \
          bench.erl \
          bench.hrl \
          bench_generate.erl \
          bench_populate.erl \
          bench_trans.erl \
          bench.config1 \
          bench.config2 \
          bench.config3 \
          bench.config4 \
          bench.config5 \
          bench.config6 \
          bench.config7 \
          "/usr/local/lib/erlang/lib/mnesia-4.14.1/examples/bench")
(cd bench; /usr/bin/install -c bench.sh "/usr/local/lib/erlang/lib/mnesia-4.14.1/examples/bench")
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "mnesia-4.14.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep mnesia-4.14.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo mnesia-4.14.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
=== Leaving application mnesia
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
=== Entering application crypto
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/crypto-3.7.1/src"
/usr/bin/install -c -m 644 crypto.erl crypto_ec_curves.erl "/usr/local/lib/erlang/lib/crypto-3.7.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/crypto-3.7.1/ebin"
/usr/bin/install -c -m 644 ../ebin/crypto.beam ../ebin/crypto_ec_curves.beam ../ebin/crypto.app \
		../ebin/crypto.appup "/usr/local/lib/erlang/lib/crypto-3.7.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/obj"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/lib"
/usr/bin/install -c -m 644 ../priv/Makefile "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/obj"
/usr/bin/install -c ../priv/obj/x86_64-unknown-linux-gnu/crypto.o "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/obj"
/usr/bin/install -c ../priv/lib/x86_64-unknown-linux-gnu/crypto.so "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/lib"
/usr/bin/install -c ../priv/obj/x86_64-unknown-linux-gnu/crypto_callback.o "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/obj"
/usr/bin/install -c ../priv/lib/x86_64-unknown-linux-gnu/crypto_callback.so "/usr/local/lib/erlang/lib/crypto-3.7.1/priv/lib"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "crypto-3.7.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep crypto-3.7.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo crypto-3.7.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
=== Leaving application crypto
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
=== Entering application orber
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/ebin"
/usr/bin/install -c -m 644 ../../ebin/oe_cos_naming_ext.beam ../../ebin/CosNaming_NamingContextExt.beam ../../ebin/CosNaming_NamingContextExt_InvalidAddress.beam ../../ebin/oe_cos_naming.beam ../../ebin/CosNaming_Name.beam ../../ebin/CosNaming_NamingContext.beam ../../ebin/CosNaming_BindingIterator.beam ../../ebin/CosNaming_NameComponent.beam ../../ebin/CosNaming_Binding.beam ../../ebin/CosNaming_BindingList.beam ../../ebin/CosNaming_NamingContext_NotFound.beam ../../ebin/CosNaming_NamingContext_AlreadyBound.beam ../../ebin/CosNaming_NamingContext_CannotProceed.beam ../../ebin/CosNaming_NamingContext_InvalidName.beam ../../ebin/CosNaming_NamingContext_NotEmpty.beam ../../ebin/CosNaming_NamingContextExt_impl.beam ../../ebin/CosNaming_BindingIterator_impl.beam ../../ebin/lname.beam ../../ebin/lname_component.beam ../../ebin/orber_cosnaming_utils.beam   "/usr/local/lib/erlang/lib/orber-3.8.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/COSS/CosNaming"
/usr/bin/install -c -m 644 CosNaming_NamingContextExt_impl.erl CosNaming_BindingIterator_impl.erl lname.erl lname_component.erl orber_cosnaming_utils.erl  lname.hrl orber_cosnaming.hrl cos_naming.idl cos_naming_ext.idl "/usr/local/lib/erlang/lib/orber-3.8.2/COSS/CosNaming"
/usr/bin/install -c -m 644 oe_cos_naming.erl CosNaming_Name.erl CosNaming_NamingContext.erl CosNaming_BindingIterator.erl CosNaming_NameComponent.erl CosNaming_Binding.erl CosNaming_BindingList.erl CosNaming_NamingContext_NotFound.erl CosNaming_NamingContext_AlreadyBound.erl CosNaming_NamingContext_CannotProceed.erl CosNaming_NamingContext_InvalidName.erl CosNaming_NamingContext_NotEmpty.erl oe_cos_naming.hrl CosNaming.hrl CosNaming_NamingContext.hrl CosNaming_BindingIterator.hrl oe_cos_naming_ext.erl CosNaming_NamingContextExt.erl CosNaming_NamingContextExt_InvalidAddress.erl oe_cos_naming_ext.hrl CosNaming_NamingContextExt.hrl "/usr/local/lib/erlang/lib/orber-3.8.2/COSS/CosNaming"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_erlang.beam ../ebin/erlang_pid.beam ../ebin/erlang_port.beam ../ebin/erlang_ref.beam ../ebin/erlang_binary.beam ../ebin/oe_CORBA.beam ../ebin/oe_OrberIFR.beam ../ebin/OrberApp_IFR.beam ../ebin/orber.beam ../ebin/corba.beam ../ebin/corba_boa.beam ../ebin/corba_object.beam ../ebin/any.beam ../ebin/iop_ior.beam ../ebin/orber_tc.beam ../ebin/orber_typedefs.beam ../ebin/orber_request_number.beam ../ebin/orber_objectkeys.beam ../ebin/orber_initial_references.beam ../ebin/cdrlib.beam ../ebin/cdr_encode.beam ../ebin/cdr_decode.beam ../ebin/orber_iiop.beam ../ebin/orber_iiop_net.beam ../ebin/orber_iiop_net_accept.beam ../ebin/orber_iiop_insup.beam ../ebin/orber_iiop_inproxy.beam ../ebin/orber_iiop_inrequest.beam ../ebin/orber_iiop_pm.beam ../ebin/orber_iiop_outsup.beam ../ebin/orber_iiop_outproxy.beam ../ebin/orber_iiop_socketsup.beam ../ebin/orber_socket.beam ../ebin/orber_ifr.beam ../ebin/orber_ifr_aliasdef.beam ../ebin/orber_ifr_arraydef.beam ../ebin/orber_ifr_attributedef.beam ../ebin/orber_ifr_constantdef.beam ../ebin/orber_ifr_contained.beam ../ebin/orber_ifr_container.beam ../ebin/orber_ifr_enumdef.beam ../ebin/orber_ifr_exceptiondef.beam ../ebin/orber_ifr_idltype.beam ../ebin/orber_ifr_interfacedef.beam ../ebin/orber_ifr_irobject.beam ../ebin/orber_ifr_moduledef.beam ../ebin/orber_ifr_operationdef.beam ../ebin/orber_ifr_orb.beam ../ebin/orber_ifr_primitivedef.beam ../ebin/orber_ifr_repository.beam ../ebin/orber_ifr_sequencedef.beam ../ebin/orber_ifr_stringdef.beam ../ebin/orber_ifr_wstringdef.beam ../ebin/orber_ifr_structdef.beam ../ebin/orber_ifr_typecode.beam ../ebin/orber_ifr_typedef.beam ../ebin/orber_ifr_uniondef.beam ../ebin/orber_ifr_fixeddef.beam ../ebin/orber_ifr_utils.beam ../ebin/OrberApp_IFR_impl.beam ../ebin/orber_pi.beam ../ebin/orber_web.beam ../ebin/orber_web_server.beam ../ebin/orber_iiop_tracer.beam ../ebin/orber_iiop_tracer_silent.beam ../ebin/orber_iiop_tracer_stealth.beam ../ebin/fixed.beam ../ebin/orber_exceptions.beam ../ebin/orber_diagnostics.beam ../ebin/orber_acl.beam ../ebin/orber_env.beam ../ebin/orber_tb.beam ../ebin/orber.app ../ebin/orber.appup "/usr/local/lib/erlang/lib/orber-3.8.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/src"
/usr/bin/install -c -m 644 orber.erl corba.erl corba_boa.erl corba_object.erl any.erl iop_ior.erl orber_tc.erl orber_typedefs.erl orber_request_number.erl orber_objectkeys.erl orber_initial_references.erl cdrlib.erl cdr_encode.erl cdr_decode.erl orber_iiop.erl orber_iiop_net.erl orber_iiop_net_accept.erl orber_iiop_insup.erl orber_iiop_inproxy.erl orber_iiop_inrequest.erl orber_iiop_pm.erl orber_iiop_outsup.erl orber_iiop_outproxy.erl orber_iiop_socketsup.erl orber_socket.erl orber_ifr.erl orber_ifr_aliasdef.erl orber_ifr_arraydef.erl orber_ifr_attributedef.erl orber_ifr_constantdef.erl orber_ifr_contained.erl orber_ifr_container.erl orber_ifr_enumdef.erl orber_ifr_exceptiondef.erl orber_ifr_idltype.erl orber_ifr_interfacedef.erl orber_ifr_irobject.erl orber_ifr_moduledef.erl orber_ifr_operationdef.erl orber_ifr_orb.erl orber_ifr_primitivedef.erl orber_ifr_repository.erl orber_ifr_sequencedef.erl orber_ifr_stringdef.erl orber_ifr_wstringdef.erl orber_ifr_structdef.erl orber_ifr_typecode.erl orber_ifr_typedef.erl orber_ifr_uniondef.erl orber_ifr_fixeddef.erl orber_ifr_utils.erl OrberApp_IFR_impl.erl orber_pi.erl orber_web.erl orber_web_server.erl orber_iiop_tracer.erl orber_iiop_tracer_silent.erl orber_iiop_tracer_stealth.erl fixed.erl orber_exceptions.erl orber_diagnostics.erl orber_acl.erl orber_env.erl orber_tb.erl	  CORBA.hrl oe_CORBA.hrl OrberApp_IFR.hrl oe_OrberIFR.hrl OrberApp.hrl  orber_iiop.hrl ifr_objects.hrl orber_ifr.hrl "/usr/local/lib/erlang/lib/orber-3.8.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/include"
/usr/bin/install -c -m 644 ../include/corba.hrl ../include/ifr_types.hrl ../include/orber_pi.hrl oe_erlang.hrl erlang.hrl "/usr/local/lib/erlang/lib/orber-3.8.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/java_src/Orber"
/usr/bin/install -c -m 644 InitialReference.java "/usr/local/lib/erlang/lib/orber-3.8.2/java_src/Orber"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/priv/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/priv/include"
/usr/bin/install -c -m 644 InitialReference.cc "/usr/local/lib/erlang/lib/orber-3.8.2/priv/src"
/usr/bin/install -c -m 644 InitialReference.hh "/usr/local/lib/erlang/lib/orber-3.8.2/priv/include"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/examples/Stack"
/usr/bin/install -c -m 644 StackModule_Stack_impl.erl StackModule_StackFactory_impl.erl stack_factory.erl stack_client.erl StackClient.java StackClient.cc stack.idl InitialReferences.idl "/usr/local/lib/erlang/lib/orber-3.8.2/examples/Stack"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/orber-3.8.2/priv"
/usr/bin/install -c -m 644 orber_help.txt orber.tool blank.html info_frames.html main_frame.html start_info.html "/usr/local/lib/erlang/lib/orber-3.8.2/priv"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "orber-3.8.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep orber-3.8.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo orber-3.8.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
=== Leaving application orber
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
=== Entering application os_mon
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/src"
/usr/bin/install -c -m 644 disksup.erl memsup.erl cpu_sup.erl os_mon.erl os_mon_mib.erl os_sup.erl os_mon_sysinfo.erl nteventlog.erl "/usr/local/lib/erlang/lib/os_mon-2.4.1/src"
/usr/bin/install -c -m 644 ../include/memsup.hrl "/usr/local/lib/erlang/lib/os_mon-2.4.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/ebin"
/usr/bin/install -c -m 644 ../ebin/disksup.beam ../ebin/memsup.beam ../ebin/cpu_sup.beam ../ebin/os_mon.beam ../ebin/os_mon_mib.beam ../ebin/os_sup.beam ../ebin/os_mon_sysinfo.beam ../ebin/nteventlog.beam ../ebin/os_mon.app ../ebin/os_mon.appup "/usr/local/lib/erlang/lib/os_mon-2.4.1/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
 MAKE	release
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
 MAKE	release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/src"
/usr/bin/install -c -m 644 memsup.c cpu_sup.c "/usr/local/lib/erlang/lib/os_mon-2.4.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/priv/bin"
/usr/bin/install -c ../priv/bin/x86_64-unknown-linux-gnu/memsup ../priv/bin/x86_64-unknown-linux-gnu/cpu_sup "/usr/local/lib/erlang/lib/os_mon-2.4.1/priv/bin"
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/mibs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/mibs/v1"
/usr/bin/install -c -m 644 OTP-OS-MON-MIB.mib  OTP-OS-MON-MIB.funcs "/usr/local/lib/erlang/lib/os_mon-2.4.1/mibs"
/usr/bin/install -c -m 644 v1/OTP-OS-MON-MIB.mib.v1 "/usr/local/lib/erlang/lib/os_mon-2.4.1/mibs/v1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/include"
/usr/bin/install -c -m 644 ../include/OTP-OS-MON-MIB.hrl "/usr/local/lib/erlang/lib/os_mon-2.4.1/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/os_mon-2.4.1/priv/mibs"
/usr/bin/install -c -m 644 ../priv/mibs/OTP-OS-MON-MIB.bin "/usr/local/lib/erlang/lib/os_mon-2.4.1/priv/mibs"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "os_mon-2.4.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep os_mon-2.4.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo os_mon-2.4.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
=== Leaving application os_mon
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
=== Entering application syntax_tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/syntax_tools-2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/erl_syntax.beam ../ebin/erl_prettypr.beam ../ebin/erl_syntax_lib.beam ../ebin/erl_comment_scan.beam ../ebin/erl_recomment.beam ../ebin/erl_tidy.beam ../ebin/epp_dodger.beam ../ebin/prettypr.beam ../ebin/igor.beam ../ebin/merl.beam ../ebin/merl_transform.beam ../ebin/syntax_tools.app ../ebin/syntax_tools.appup "/usr/local/lib/erlang/lib/syntax_tools-2.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/syntax_tools-2.1/src"
/usr/bin/install -c -m 644 erl_syntax.erl erl_prettypr.erl erl_syntax_lib.erl erl_comment_scan.erl erl_recomment.erl erl_tidy.erl epp_dodger.erl prettypr.erl igor.erl merl.erl merl_transform.erl "/usr/local/lib/erlang/lib/syntax_tools-2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/syntax_tools-2.1/include"
/usr/bin/install -c -m 644 ../include/merl.hrl "/usr/local/lib/erlang/lib/syntax_tools-2.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/syntax_tools-2.1/examples"
/usr/bin/install -c -m 644 demo.erl "/usr/local/lib/erlang/lib/syntax_tools-2.1/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "syntax_tools-2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep syntax_tools-2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo syntax_tools-2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
=== Leaving application syntax_tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/syntax_tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
=== Entering application public_key
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/include"
/usr/bin/install -c -m 644 ../include/OTP-PUB-KEY.hrl ../include/PKCS-FRAME.hrl "/usr/local/lib/erlang/lib/public_key-1.2/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/asn1"
/usr/bin/install -c -m 644 PKIX1Explicit88.asn1 PKIX1Implicit88.asn1 PKIX1Algorithms88.asn1 PKIXAttributeCertificate.asn1 PKCS-1.asn1 PKCS-3.asn1 PKCS-7.asn1 PKCS-8.asn1 PKCS-10.asn1 PKCS5v2-0.asn1 OTP-PKIX.asn1 InformationFramework.asn1 RFC5639.asn1 OTP-PUB-KEY.erl PKCS-FRAME.erl OTP-PUB-KEY.hrl PKCS-FRAME.hrl OTP-PUB-KEY.asn1config \
		  "/usr/local/lib/erlang/lib/public_key-1.2/asn1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/ebin"
/usr/bin/install -c -m 644 ../ebin/OTP-PUB-KEY.beam ../ebin/PKCS-FRAME.beam "/usr/local/lib/erlang/lib/public_key-1.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/src"
/usr/bin/install -c -m 644 pubkey_moduli.hrl public_key.erl pubkey_pem.erl pubkey_ssh.erl pubkey_pbe.erl pubkey_cert.erl pubkey_cert_records.erl pubkey_crl.erl "/usr/local/lib/erlang/lib/public_key-1.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/include"
/usr/bin/install -c -m 644 ../include/public_key.hrl  "/usr/local/lib/erlang/lib/public_key-1.2/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/public_key-1.2/ebin"
/usr/bin/install -c -m 644 ../ebin/public_key.beam ../ebin/pubkey_pem.beam ../ebin/pubkey_ssh.beam ../ebin/pubkey_pbe.beam ../ebin/pubkey_cert.beam ../ebin/pubkey_cert_records.beam ../ebin/pubkey_crl.beam ../ebin/public_key.app ../ebin/public_key.appup "/usr/local/lib/erlang/lib/public_key-1.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "public_key-1.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep public_key-1.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo public_key-1.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
=== Leaving application public_key
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
=== Entering application ssl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssl-8.0.2/src"
/usr/bin/install -c -m 644 ssl.erl tls.erl dtls.erl ssl_alert.erl ssl_app.erl ssl_dist_sup.erl ssl_sup.erl inet_tls_dist.erl inet6_tls_dist.erl ssl_certificate.erl ssl_pkix_db.erl ssl_cipher.erl ssl_srp_primes.erl tls_connection.erl dtls_connection.erl ssl_config.erl ssl_connection.erl tls_connection_sup.erl dtls_connection_sup.erl tls_handshake.erl dtls_handshake.erl ssl_handshake.erl ssl_manager.erl ssl_session.erl ssl_session_cache.erl ssl_crl.erl ssl_crl_cache.erl ssl_crl_hash_dir.erl ssl_socket.erl ssl_listen_tracker_sup.erl tls_record.erl dtls_record.erl ssl_record.erl ssl_v2.erl ssl_v3.erl tls_v1.erl dtls_v1.erl ssl_tls_dist_proxy.erl ssl_session_cache_api.erl ssl_crl_cache_api.erl ssl_alert.hrl ssl_cipher.hrl tls_connection.hrl dtls_connection.hrl ssl_connection.hrl ssl_handshake.hrl tls_handshake.hrl dtls_handshake.hrl ssl_api.hrl ssl_internal.hrl ssl_record.hrl tls_record.hrl dtls_record.hrl ssl_srp.hrl "/usr/local/lib/erlang/lib/ssl-8.0.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssl-8.0.2/ebin"
/usr/bin/install -c -m 644 ../ebin/ssl_session_cache_api.beam ../ebin/ssl_crl_cache_api.beam ../ebin/ssl.beam ../ebin/tls.beam ../ebin/dtls.beam ../ebin/ssl_alert.beam ../ebin/ssl_app.beam ../ebin/ssl_dist_sup.beam ../ebin/ssl_sup.beam ../ebin/inet_tls_dist.beam ../ebin/inet6_tls_dist.beam ../ebin/ssl_certificate.beam ../ebin/ssl_pkix_db.beam ../ebin/ssl_cipher.beam ../ebin/ssl_srp_primes.beam ../ebin/tls_connection.beam ../ebin/dtls_connection.beam ../ebin/ssl_config.beam ../ebin/ssl_connection.beam ../ebin/tls_connection_sup.beam ../ebin/dtls_connection_sup.beam ../ebin/tls_handshake.beam ../ebin/dtls_handshake.beam ../ebin/ssl_handshake.beam ../ebin/ssl_manager.beam ../ebin/ssl_session.beam ../ebin/ssl_session_cache.beam ../ebin/ssl_crl.beam ../ebin/ssl_crl_cache.beam ../ebin/ssl_crl_hash_dir.beam ../ebin/ssl_socket.beam ../ebin/ssl_listen_tracker_sup.beam ../ebin/tls_record.beam ../ebin/dtls_record.beam ../ebin/ssl_record.beam ../ebin/ssl_v2.beam ../ebin/ssl_v3.beam ../ebin/tls_v1.beam ../ebin/dtls_v1.beam ../ebin/ssl_tls_dist_proxy.beam ../ebin/ssl.app \
	../ebin/ssl.appup "/usr/local/lib/erlang/lib/ssl-8.0.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssl-8.0.2/examples/certs"
tar cf - etc | \
		(cd "/usr/local/lib/erlang/lib/ssl-8.0.2/examples/certs"; tar xf -)
chmod -R ug+rw "/usr/local/lib/erlang/lib/ssl-8.0.2/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssl-8.0.2/examples/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssl-8.0.2/examples/ebin"
(cd ..; tar cf - src ebin  | (cd "/usr/local/lib/erlang/lib/ssl-8.0.2/examples"; tar xf -))
chmod -R ug+w "/usr/local/lib/erlang/lib/ssl-8.0.2/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "ssl-8.0.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep ssl-8.0.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo ssl-8.0.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
=== Leaving application ssl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
=== Entering application observer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/src"
/usr/bin/install -c -m 644 crashdump_viewer.erl cdv_atom_cb.erl cdv_bin_cb.erl cdv_detail_wx.erl cdv_dist_cb.erl cdv_ets_cb.erl cdv_fun_cb.erl cdv_gen_cb.erl cdv_html_wx.erl cdv_info_wx.erl cdv_int_tab_cb.erl cdv_mem_cb.erl cdv_mod_cb.erl cdv_multi_wx.erl cdv_port_cb.erl cdv_proc_cb.erl cdv_sched_cb.erl cdv_table_wx.erl cdv_term_cb.erl cdv_timer_cb.erl cdv_virtual_list_wx.erl cdv_wx.erl etop.erl etop_tr.erl etop_txt.erl observer.erl observer_app_wx.erl observer_alloc_wx.erl observer_html_lib.erl observer_lib.erl observer_perf_wx.erl observer_port_wx.erl observer_pro_wx.erl observer_procinfo.erl observer_sys_wx.erl observer_trace_wx.erl observer_traceoptions_wx.erl observer_tv_table.erl observer_tv_wx.erl observer_wx.erl ttb.erl ttb_et.erl "/usr/local/lib/erlang/lib/observer-2.2.2/src"
/usr/bin/install -c -m 644 observer_tv.hrl observer_defs.hrl crashdump_viewer.hrl etop_defs.hrl "/usr/local/lib/erlang/lib/observer-2.2.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/examples"
/usr/bin/install -c -m 644 multitrace.erl "/usr/local/lib/erlang/lib/observer-2.2.2/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/include"
/usr/bin/install -c -m 644 ../include/etop.hrl "/usr/local/lib/erlang/lib/observer-2.2.2/include"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/ebin"
/usr/bin/install -c -m 644 ../ebin/crashdump_viewer.beam ../ebin/cdv_atom_cb.beam ../ebin/cdv_bin_cb.beam ../ebin/cdv_detail_wx.beam ../ebin/cdv_dist_cb.beam ../ebin/cdv_ets_cb.beam ../ebin/cdv_fun_cb.beam ../ebin/cdv_gen_cb.beam ../ebin/cdv_html_wx.beam ../ebin/cdv_info_wx.beam ../ebin/cdv_int_tab_cb.beam ../ebin/cdv_mem_cb.beam ../ebin/cdv_mod_cb.beam ../ebin/cdv_multi_wx.beam ../ebin/cdv_port_cb.beam ../ebin/cdv_proc_cb.beam ../ebin/cdv_sched_cb.beam ../ebin/cdv_table_wx.beam ../ebin/cdv_term_cb.beam ../ebin/cdv_timer_cb.beam ../ebin/cdv_virtual_list_wx.beam ../ebin/cdv_wx.beam ../ebin/etop.beam ../ebin/etop_tr.beam ../ebin/etop_txt.beam ../ebin/observer.beam ../ebin/observer_app_wx.beam ../ebin/observer_alloc_wx.beam ../ebin/observer_html_lib.beam ../ebin/observer_lib.beam ../ebin/observer_perf_wx.beam ../ebin/observer_port_wx.beam ../ebin/observer_pro_wx.beam ../ebin/observer_procinfo.beam ../ebin/observer_sys_wx.beam ../ebin/observer_trace_wx.beam ../ebin/observer_traceoptions_wx.beam ../ebin/observer_tv_table.beam ../ebin/observer_tv_wx.beam ../ebin/observer_wx.beam ../ebin/ttb.beam ../ebin/ttb_et.beam ../ebin/observer.app ../ebin/observer.appup "/usr/local/lib/erlang/lib/observer-2.2.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/priv/bin"
/usr/bin/install -c ../priv/bin/etop ../priv/bin/cdv  "/usr/local/lib/erlang/lib/observer-2.2.2/priv/bin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/observer-2.2.2/priv/crashdump_viewer"
/usr/bin/install -c -m 644 ../priv/crashdump_viewer.tool ../priv/erlang_observer.png "/usr/local/lib/erlang/lib/observer-2.2.2/priv"
/usr/bin/install -c -m 644 ../priv/crashdump_viewer/collapsd.gif ../priv/crashdump_viewer/exploded.gif "/usr/local/lib/erlang/lib/observer-2.2.2/priv/crashdump_viewer"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "observer-2.2.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep observer-2.2.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo observer-2.2.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
=== Leaving application observer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
=== Skipping subdir odbc, reason:
ODBC library - link check failed
===
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
=== Entering application diameter
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
for d in bin ebin examples include src/dict; do \
	    /usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/$d"; \
	done
/usr/bin/install -c ../bin/diameterc "/usr/local/lib/erlang/lib/diameter-1.12.1/bin"
/usr/bin/install -c -m 644  ../ebin/diameter.beam  ../ebin/diameter_app.beam  ../ebin/diameter_callback.beam  ../ebin/diameter_capx.beam  ../ebin/diameter_config.beam  ../ebin/diameter_config_sup.beam  ../ebin/diameter_codec.beam  ../ebin/diameter_dict.beam  ../ebin/diameter_lib.beam  ../ebin/diameter_misc_sup.beam  ../ebin/diameter_peer.beam  ../ebin/diameter_peer_fsm.beam  ../ebin/diameter_peer_fsm_sup.beam  ../ebin/diameter_reg.beam  ../ebin/diameter_service.beam  ../ebin/diameter_service_sup.beam  ../ebin/diameter_session.beam  ../ebin/diameter_stats.beam  ../ebin/diameter_sup.beam  ../ebin/diameter_sync.beam  ../ebin/diameter_traffic.beam  ../ebin/diameter_types.beam  ../ebin/diameter_watchdog.beam  ../ebin/diameter_watchdog_sup.beam  ../ebin/diameter_etcp.beam  ../ebin/diameter_etcp_sup.beam  ../ebin/diameter_tcp.beam  ../ebin/diameter_tcp_sup.beam  ../ebin/diameter_sctp.beam  ../ebin/diameter_sctp_sup.beam  ../ebin/diameter_transport.beam  ../ebin/diameter_transport_sup.beam  ../ebin/diameter_gen_base_rfc3588.beam  ../ebin/diameter_gen_base_rfc6733.beam  ../ebin/diameter_gen_base_accounting.beam  ../ebin/diameter_gen_acct_rfc6733.beam  ../ebin/diameter_gen_relay.beam  ../ebin/diameter_codegen.beam  ../ebin/diameter_exprecs.beam  ../ebin/diameter_dict_scanner.beam  ../ebin/diameter_dict_util.beam  ../ebin/diameter_make.beam  ../ebin/diameter_dbg.beam  ../ebin/diameter_info.beam  ../ebin/diameter_dict_parser.beam ../ebin/diameter.app ../ebin/diameter.appup "/usr/local/lib/erlang/lib/diameter-1.12.1/ebin"
/usr/bin/install -c -m 644 ../include/diameter.hrl ../include/diameter_gen.hrl gen/diameter_gen_base_rfc3588.hrl gen/diameter_gen_base_rfc6733.hrl gen/diameter_gen_base_accounting.hrl gen/diameter_gen_acct_rfc6733.hrl gen/diameter_gen_relay.hrl \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/include"
/usr/bin/install -c -m 644 dict/base_rfc3588.dia dict/base_rfc6733.dia dict/base_accounting.dia dict/acct_rfc6733.dia dict/relay.dia "/usr/local/lib/erlang/lib/diameter-1.12.1/src/dict"
make release_src_base release_src_compiler release_src_gen release_src_info release_src_transport
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/src/base"
/usr/bin/install -c -m 644 base/diameter.erl base/diameter_app.erl base/diameter_callback.erl base/diameter_capx.erl base/diameter_config.erl base/diameter_config_sup.erl base/diameter_codec.erl base/diameter_dict.erl base/diameter_lib.erl base/diameter_misc_sup.erl base/diameter_peer.erl base/diameter_peer_fsm.erl base/diameter_peer_fsm_sup.erl base/diameter_reg.erl base/diameter_service.erl base/diameter_service_sup.erl base/diameter_session.erl base/diameter_stats.erl base/diameter_sup.erl base/diameter_sync.erl base/diameter_traffic.erl base/diameter_types.erl base/diameter_watchdog.erl base/diameter_watchdog_sup.erl base/diameter_internal.hrl \
	                 \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/src/base"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/src/compiler"
/usr/bin/install -c -m 644 compiler/diameter_codegen.erl compiler/diameter_exprecs.erl compiler/diameter_dict_scanner.erl compiler/diameter_dict_util.erl compiler/diameter_make.erl compiler/diameter_forms.hrl compiler/diameter_vsn.hrl \
	                compiler/diameter_dict_parser.yrl \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/src/compiler"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/src/gen"
/usr/bin/install -c -m 644 gen/diameter_gen_base_rfc3588.erl gen/diameter_gen_base_rfc6733.erl gen/diameter_gen_base_accounting.erl gen/diameter_gen_acct_rfc6733.erl gen/diameter_gen_relay.erl gen/diameter_dict_parser.erl \
	                 \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/src/gen"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/src/info"
/usr/bin/install -c -m 644 info/diameter_dbg.erl info/diameter_info.erl \
	                 \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/src/info"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/src/transport"
/usr/bin/install -c -m 644 transport/diameter_etcp.erl transport/diameter_etcp_sup.erl transport/diameter_tcp.erl transport/diameter_tcp_sup.erl transport/diameter_sctp.erl transport/diameter_sctp_sup.erl transport/diameter_transport.erl transport/diameter_transport_sup.erl \
	                 \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/src/transport"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make release_examples_code release_examples_dict
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/examples/code"
/usr/bin/install -c -m 644  ../examples/code/GNUmakefile  ../examples/code/node.erl  ../examples/code/client.erl  ../examples/code/client_cb.erl  ../examples/code/server.erl  ../examples/code/server_cb.erl  ../examples/code/relay.erl  ../examples/code/relay_cb.erl \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/examples/code"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/diameter-1.12.1/examples/dict"
/usr/bin/install -c -m 644  ../examples/dict/rfc4004_mip.dia  ../examples/dict/rfc4005_nas.dia  ../examples/dict/rfc4006_cc.dia  ../examples/dict/rfc4072_eap.dia  ../examples/dict/rfc4590_digest.dia  ../examples/dict/rfc4740_sip.dia \
	                "/usr/local/lib/erlang/lib/diameter-1.12.1/examples/dict"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "diameter-1.12.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep diameter-1.12.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo diameter-1.12.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
=== Leaving application diameter
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
=== Entering application cosTransactions
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosTransactions.beam ../ebin/CosTransactions_Control.beam ../ebin/CosTransactions_Coordinator.beam ../ebin/CosTransactions_HeuristicCommit.beam ../ebin/CosTransactions_HeuristicHazard.beam ../ebin/CosTransactions_HeuristicMixed.beam ../ebin/CosTransactions_HeuristicRollback.beam ../ebin/CosTransactions_Inactive.beam ../ebin/CosTransactions_InvalidControl.beam ../ebin/CosTransactions_NoTransaction.beam ../ebin/CosTransactions_NotPrepared.beam ../ebin/CosTransactions_NotSubtransaction.beam ../ebin/CosTransactions_RecoveryCoordinator.beam ../ebin/CosTransactions_Resource.beam ../ebin/CosTransactions_SubtransactionAwareResource.beam ../ebin/CosTransactions_SubtransactionsUnavailable.beam ../ebin/CosTransactions_Terminator.beam ../ebin/CosTransactions_TransactionFactory.beam ../ebin/CosTransactions_Unavailable.beam ../ebin/CosTransactions_SynchronizationUnavailable.beam ../ebin/CosTransactions_TransIdentity.beam ../ebin/CosTransactions_PropagationContext.beam ../ebin/CosTransactions_otid_t.beam ../ebin/CosTransactions_WrongTransaction.beam ../ebin/ETraP_Server.beam ../ebin/ETraP_Common.beam ../ebin/etrap_logmgr.beam ../ebin/ETraP_Server_impl.beam ../ebin/CosTransactions_Terminator_impl.beam ../ebin/CosTransactions_TransactionFactory_impl.beam ../ebin/cosTransactions.beam  ../ebin/cosTransactions.app ../ebin/cosTransactions.appup "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/src"
/usr/bin/install -c -m 644 ETraP_Common.erl etrap_logmgr.erl ETraP_Server_impl.erl CosTransactions_Terminator_impl.erl CosTransactions_TransactionFactory_impl.erl cosTransactions.erl  ETraP_Common.hrl oe_CosTransactions.erl CosTransactions_Control.erl CosTransactions_Coordinator.erl CosTransactions_HeuristicCommit.erl CosTransactions_HeuristicHazard.erl CosTransactions_HeuristicMixed.erl CosTransactions_HeuristicRollback.erl CosTransactions_Inactive.erl CosTransactions_InvalidControl.erl CosTransactions_NoTransaction.erl CosTransactions_NotPrepared.erl CosTransactions_NotSubtransaction.erl CosTransactions_RecoveryCoordinator.erl CosTransactions_Resource.erl CosTransactions_SubtransactionAwareResource.erl CosTransactions_SubtransactionsUnavailable.erl CosTransactions_Terminator.erl CosTransactions_TransactionFactory.erl CosTransactions_Unavailable.erl CosTransactions_SynchronizationUnavailable.erl CosTransactions_TransIdentity.erl CosTransactions_PropagationContext.erl CosTransactions_otid_t.erl CosTransactions_WrongTransaction.erl ETraP_Server.erl CosTransactions.idl "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/include"
/usr/bin/install -c -m 644 ../include/oe_CosTransactions.hrl ../include/CosTransactions.hrl ../include/CosTransactions_Control.hrl ../include/CosTransactions_Coordinator.hrl ../include/CosTransactions_RecoveryCoordinator.hrl ../include/CosTransactions_Resource.hrl ../include/CosTransactions_SubtransactionAwareResource.hrl ../include/CosTransactions_Terminator.hrl ../include/CosTransactions_TransactionFactory.hrl ../include/ETraP.hrl ../include/ETraP_Server.hrl "/usr/local/lib/erlang/lib/cosTransactions-1.3.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosTransactions-1.3.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosTransactions-1.3.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosTransactions-1.3.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
=== Leaving application cosTransactions
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
=== Entering application cosEvent
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEvent-2.2.1"
/usr/bin/install -c -m 644 ../info "/usr/local/lib/erlang/lib/cosEvent-2.2.1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEvent-2.2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosEventChannelAdmin.beam ../ebin/CosEventChannelAdmin_ConsumerAdmin.beam ../ebin/CosEventChannelAdmin_EventChannel.beam ../ebin/CosEventChannelAdmin_ProxyPullConsumer.beam ../ebin/CosEventChannelAdmin_ProxyPullSupplier.beam ../ebin/CosEventChannelAdmin_ProxyPushConsumer.beam ../ebin/CosEventChannelAdmin_ProxyPushSupplier.beam ../ebin/CosEventChannelAdmin_SupplierAdmin.beam ../ebin/CosEventChannelAdmin_AlreadyConnected.beam ../ebin/CosEventChannelAdmin_TypeError.beam ../ebin/oe_CosEventComm_CAdmin.beam ../ebin/oe_CosEventComm_Channel.beam ../ebin/oe_CosEventComm_Event.beam ../ebin/oe_CosEventComm_PullerS.beam ../ebin/oe_CosEventComm_PusherS.beam ../ebin/oe_cosEventApp.beam ../ebin/oe_CosEventComm.beam ../ebin/CosEventComm_Disconnected.beam ../ebin/CosEventComm_PullConsumer.beam ../ebin/CosEventComm_PullSupplier.beam ../ebin/CosEventComm_PushConsumer.beam ../ebin/CosEventComm_PushSupplier.beam ../ebin/CosEventChannelAdmin_ProxyPullConsumer_impl.beam ../ebin/CosEventChannelAdmin_ProxyPushConsumer_impl.beam ../ebin/CosEventChannelAdmin_SupplierAdmin_impl.beam ../ebin/oe_CosEventComm_CAdmin_impl.beam ../ebin/oe_CosEventComm_Channel_impl.beam ../ebin/oe_CosEventComm_PullerS_impl.beam ../ebin/oe_CosEventComm_PusherS_impl.beam ../ebin/cosEventApp.beam  ../ebin/cosEvent.app ../ebin/cosEvent.appup "/usr/local/lib/erlang/lib/cosEvent-2.2.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEvent-2.2.1/src"
/usr/bin/install -c -m 644 CosEventChannelAdmin_ProxyPullConsumer_impl.erl CosEventChannelAdmin_ProxyPushConsumer_impl.erl CosEventChannelAdmin_SupplierAdmin_impl.erl oe_CosEventComm_CAdmin_impl.erl oe_CosEventComm_Channel_impl.erl oe_CosEventComm_PullerS_impl.erl oe_CosEventComm_PusherS_impl.erl cosEventApp.erl  cosEventApp.hrl oe_CosEventChannelAdmin.erl CosEventChannelAdmin_ConsumerAdmin.erl CosEventChannelAdmin_EventChannel.erl CosEventChannelAdmin_ProxyPullConsumer.erl CosEventChannelAdmin_ProxyPullSupplier.erl CosEventChannelAdmin_ProxyPushConsumer.erl CosEventChannelAdmin_ProxyPushSupplier.erl CosEventChannelAdmin_SupplierAdmin.erl CosEventChannelAdmin_AlreadyConnected.erl CosEventChannelAdmin_TypeError.erl oe_CosEventComm_CAdmin.erl oe_CosEventComm_Channel.erl oe_CosEventComm_Event.erl oe_CosEventComm_PullerS.erl oe_CosEventComm_PusherS.erl oe_cosEventApp.erl oe_CosEventComm.erl CosEventComm_Disconnected.erl CosEventComm_PullConsumer.erl CosEventComm_PullSupplier.erl CosEventComm_PushConsumer.erl CosEventComm_PushSupplier.erl CosEventChannelAdmin.idl CosEventComm.idl cosEventApp.idl "/usr/local/lib/erlang/lib/cosEvent-2.2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEvent-2.2.1/include"
/usr/bin/install -c -m 644 ../include/oe_CosEventChannelAdmin.hrl ../include/CosEventChannelAdmin.hrl ../include/CosEventChannelAdmin_ConsumerAdmin.hrl ../include/CosEventChannelAdmin_EventChannel.hrl ../include/CosEventChannelAdmin_ProxyPullConsumer.hrl ../include/CosEventChannelAdmin_ProxyPullSupplier.hrl ../include/CosEventChannelAdmin_ProxyPushConsumer.hrl ../include/CosEventChannelAdmin_ProxyPushSupplier.hrl ../include/CosEventChannelAdmin_SupplierAdmin.hrl oe_CosEventComm_PullerS.hrl oe_CosEventComm_CAdmin.hrl oe_CosEventComm_PusherS.hrl oe_CosEventComm_Channel.hrl oe_cosEventApp.hrl oe_CosEventComm_Event.hrl ../include/oe_CosEventComm.hrl ../include/CosEventComm.hrl ../include/CosEventComm_PullConsumer.hrl ../include/CosEventComm_PullSupplier.hrl ../include/CosEventComm_PushConsumer.hrl ../include/CosEventComm_PushSupplier.hrl "/usr/local/lib/erlang/lib/cosEvent-2.2.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosEvent-2.2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosEvent-2.2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosEvent-2.2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
=== Leaving application cosEvent
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
=== Entering application cosTime
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTime-1.2.2/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_TimeBase.beam ../ebin/TimeBase_IntervalT.beam ../ebin/TimeBase_UtcT.beam ../ebin/oe_CosTime.beam ../ebin/CosTime_TIO.beam ../ebin/CosTime_TimeService.beam ../ebin/CosTime_TimeUnavailable.beam ../ebin/CosTime_UTO.beam ../ebin/oe_CosTimerEvent.beam ../ebin/CosTimerEvent_TimerEventHandler.beam ../ebin/CosTimerEvent_TimerEventService.beam ../ebin/CosTimerEvent_TimerEventT.beam ../ebin/cosTime.beam ../ebin/CosTime_TIO_impl.beam ../ebin/CosTime_TimeService_impl.beam ../ebin/CosTime_UTO_impl.beam ../ebin/CosTimerEvent_TimerEventHandler_impl.beam ../ebin/CosTimerEvent_TimerEventService_impl.beam  ../ebin/cosTime.app ../ebin/cosTime.appup "/usr/local/lib/erlang/lib/cosTime-1.2.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTime-1.2.2/src"
/usr/bin/install -c -m 644 ../include/oe_TimeBase.hrl ../include/TimeBase.hrl ../include/oe_CosTime.hrl ../include/CosTime.hrl ../include/CosTime_TIO.hrl ../include/CosTime_TimeService.hrl ../include/CosTime_UTO.hrl ../include/oe_CosTimerEvent.hrl ../include/CosTimerEvent.hrl ../include/CosTimerEvent_TimerEventHandler.hrl ../include/CosTimerEvent_TimerEventService.hrl  oe_TimeBase.erl TimeBase_IntervalT.erl TimeBase_UtcT.erl oe_CosTime.erl CosTime_TIO.erl CosTime_TimeService.erl CosTime_TimeUnavailable.erl CosTime_UTO.erl  oe_CosTimerEvent.erl CosTimerEvent_TimerEventHandler.erl CosTimerEvent_TimerEventService.erl CosTimerEvent_TimerEventT.erl  TimeBase.idl CosTime.idl CosTimerEvent.idl "/usr/local/lib/erlang/lib/cosTime-1.2.2/src"
/usr/bin/install -c -m 644 cosTime.erl CosTime_TIO_impl.erl CosTime_TimeService_impl.erl CosTime_UTO_impl.erl CosTimerEvent_TimerEventHandler_impl.erl CosTimerEvent_TimerEventService_impl.erl  cosTimeApp.hrl  oe_TimeBase.erl TimeBase_IntervalT.erl TimeBase_UtcT.erl oe_CosTime.erl CosTime_TIO.erl CosTime_TimeService.erl CosTime_TimeUnavailable.erl CosTime_UTO.erl  oe_CosTimerEvent.erl CosTimerEvent_TimerEventHandler.erl CosTimerEvent_TimerEventService.erl CosTimerEvent_TimerEventT.erl  TimeBase.idl CosTime.idl CosTimerEvent.idl "/usr/local/lib/erlang/lib/cosTime-1.2.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosTime-1.2.2/include"
/usr/bin/install -c -m 644 ../include/oe_TimeBase.hrl ../include/TimeBase.hrl ../include/oe_CosTime.hrl ../include/CosTime.hrl ../include/CosTime_TIO.hrl ../include/CosTime_TimeService.hrl ../include/CosTime_UTO.hrl ../include/oe_CosTimerEvent.hrl ../include/CosTimerEvent.hrl ../include/CosTimerEvent_TimerEventHandler.hrl ../include/CosTimerEvent_TimerEventService.hrl  "/usr/local/lib/erlang/lib/cosTime-1.2.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosTime-1.2.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosTime-1.2.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosTime-1.2.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
=== Leaving application cosTime
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
=== Entering application cosNotification
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosNotification-1.2.2/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosNotification.beam ../ebin/CosNotification.beam ../ebin/CosNotification_AdminPropertiesAdmin.beam ../ebin/CosNotification_EventHeader.beam ../ebin/CosNotification_EventType.beam ../ebin/CosNotification_FixedEventHeader.beam ../ebin/CosNotification_NamedPropertyRange.beam ../ebin/CosNotification_Property.beam ../ebin/CosNotification_PropertyError.beam ../ebin/CosNotification_PropertyRange.beam ../ebin/CosNotification_QoSAdmin.beam ../ebin/CosNotification_StructuredEvent.beam ../ebin/CosNotification_UnsupportedAdmin.beam ../ebin/CosNotification_UnsupportedQoS.beam ../ebin/CosNotification_EventBatch.beam ../ebin/CosNotification_EventTypeSeq.beam ../ebin/CosNotification_NamedPropertyRangeSeq.beam ../ebin/CosNotification_PropertyErrorSeq.beam ../ebin/CosNotification_PropertySeq.beam ../ebin/oe_cosNotificationAppComm.beam ../ebin/oe_CosNotificationComm_Event.beam ../ebin/oe_CosNotifyComm.beam ../ebin/CosNotifyComm_InvalidEventType.beam ../ebin/CosNotifyComm_NotifyPublish.beam ../ebin/CosNotifyComm_NotifySubscribe.beam ../ebin/CosNotifyComm_PullConsumer.beam ../ebin/CosNotifyComm_PullSupplier.beam ../ebin/CosNotifyComm_PushConsumer.beam ../ebin/CosNotifyComm_PushSupplier.beam ../ebin/CosNotifyComm_SequencePullConsumer.beam ../ebin/CosNotifyComm_SequencePullSupplier.beam ../ebin/CosNotifyComm_SequencePushConsumer.beam ../ebin/CosNotifyComm_SequencePushSupplier.beam ../ebin/CosNotifyComm_StructuredPullConsumer.beam ../ebin/CosNotifyComm_StructuredPullSupplier.beam ../ebin/CosNotifyComm_StructuredPushConsumer.beam ../ebin/CosNotifyComm_StructuredPushSupplier.beam ../ebin/oe_CosNotifyFilter.beam ../ebin/CosNotifyFilter_CallbackNotFound.beam ../ebin/CosNotifyFilter_ConstraintExp.beam ../ebin/CosNotifyFilter_ConstraintInfo.beam ../ebin/CosNotifyFilter_ConstraintNotFound.beam ../ebin/CosNotifyFilter_DuplicateConstraintID.beam ../ebin/CosNotifyFilter_Filter.beam ../ebin/CosNotifyFilter_FilterAdmin.beam ../ebin/CosNotifyFilter_FilterFactory.beam ../ebin/CosNotifyFilter_FilterNotFound.beam ../ebin/CosNotifyFilter_InvalidConstraint.beam ../ebin/CosNotifyFilter_InvalidGrammar.beam ../ebin/CosNotifyFilter_InvalidValue.beam ../ebin/CosNotifyFilter_MappingConstraintInfo.beam ../ebin/CosNotifyFilter_MappingConstraintPair.beam ../ebin/CosNotifyFilter_MappingFilter.beam ../ebin/CosNotifyFilter_UnsupportedFilterableData.beam ../ebin/CosNotifyFilter_CallbackIDSeq.beam ../ebin/CosNotifyFilter_ConstraintExpSeq.beam ../ebin/CosNotifyFilter_ConstraintIDSeq.beam ../ebin/CosNotifyFilter_ConstraintInfoSeq.beam ../ebin/CosNotifyFilter_FilterIDSeq.beam ../ebin/CosNotifyFilter_MappingConstraintInfoSeq.beam ../ebin/CosNotifyFilter_MappingConstraintPairSeq.beam ../ebin/oe_CosNotifyChannelAdmin.beam ../ebin/CosNotifyChannelAdmin_AdminLimit.beam ../ebin/CosNotifyChannelAdmin_AdminLimitExceeded.beam ../ebin/CosNotifyChannelAdmin_AdminNotFound.beam ../ebin/CosNotifyChannelAdmin_ChannelNotFound.beam ../ebin/CosNotifyChannelAdmin_ConnectionAlreadyActive.beam ../ebin/CosNotifyChannelAdmin_ConnectionAlreadyInactive.beam ../ebin/CosNotifyChannelAdmin_ConsumerAdmin.beam ../ebin/CosNotifyChannelAdmin_EventChannel.beam ../ebin/CosNotifyChannelAdmin_EventChannelFactory.beam ../ebin/CosNotifyChannelAdmin_NotConnected.beam ../ebin/CosNotifyChannelAdmin_ProxyConsumer.beam ../ebin/CosNotifyChannelAdmin_ProxyNotFound.beam ../ebin/CosNotifyChannelAdmin_ProxyPullConsumer.beam ../ebin/CosNotifyChannelAdmin_ProxyPullSupplier.beam ../ebin/CosNotifyChannelAdmin_ProxyPushConsumer.beam ../ebin/CosNotifyChannelAdmin_ProxyPushSupplier.beam ../ebin/CosNotifyChannelAdmin_ProxySupplier.beam ../ebin/CosNotifyChannelAdmin_SequenceProxyPullConsumer.beam ../ebin/CosNotifyChannelAdmin_SequenceProxyPullSupplier.beam ../ebin/CosNotifyChannelAdmin_SequenceProxyPushConsumer.beam ../ebin/CosNotifyChannelAdmin_SequenceProxyPushSupplier.beam ../ebin/CosNotifyChannelAdmin_StructuredProxyPullConsumer.beam ../ebin/CosNotifyChannelAdmin_StructuredProxyPullSupplier.beam ../ebin/CosNotifyChannelAdmin_StructuredProxyPushConsumer.beam ../ebin/CosNotifyChannelAdmin_StructuredProxyPushSupplier.beam ../ebin/CosNotifyChannelAdmin_SupplierAdmin.beam ../ebin/CosNotifyChannelAdmin_AdminIDSeq.beam ../ebin/CosNotifyChannelAdmin_ChannelIDSeq.beam ../ebin/CosNotifyChannelAdmin_ProxyIDSeq.beam ../ebin/cosNotification_Grammar.beam ../ebin/CosNotification_Common.beam ../ebin/CosNotifyChannelAdmin_ConsumerAdmin_impl.beam ../ebin/CosNotifyChannelAdmin_EventChannelFactory_impl.beam ../ebin/CosNotifyChannelAdmin_EventChannel_impl.beam ../ebin/CosNotifyChannelAdmin_SupplierAdmin_impl.beam ../ebin/CosNotifyFilter_Filter_impl.beam ../ebin/CosNotifyFilter_MappingFilter_impl.beam ../ebin/CosNotifyFilter_FilterFactory_impl.beam ../ebin/PullerConsumer_impl.beam ../ebin/PullerSupplier_impl.beam ../ebin/PusherConsumer_impl.beam ../ebin/PusherSupplier_impl.beam ../ebin/cosNotificationApp.beam ../ebin/cosNotification_Scanner.beam ../ebin/cosNotification_Filter.beam ../ebin/cosNotification_eventDB.beam ../ebin/cosNotification.app ../ebin/cosNotification.appup "/usr/local/lib/erlang/lib/cosNotification-1.2.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosNotification-1.2.2/src"
/usr/bin/install -c -m 644 ../include/oe_CosNotification.hrl ../include/CosNotification.hrl ../include/CosNotification_AdminPropertiesAdmin.hrl ../include/CosNotification_QoSAdmin.hrl oe_cosNotificationAppComm.hrl oe_CosNotificationComm.hrl oe_CosNotificationComm_Event.hrl ../include/oe_CosNotifyComm.hrl ../include/CosNotifyComm.hrl ../include/CosNotifyComm_NotifyPublish.hrl ../include/CosNotifyComm_NotifySubscribe.hrl ../include/CosNotifyComm_PullConsumer.hrl ../include/CosNotifyComm_PullSupplier.hrl ../include/CosNotifyComm_PushConsumer.hrl ../include/CosNotifyComm_PushSupplier.hrl ../include/CosNotifyComm_SequencePullConsumer.hrl ../include/CosNotifyComm_SequencePullSupplier.hrl ../include/CosNotifyComm_SequencePushConsumer.hrl ../include/CosNotifyComm_SequencePushSupplier.hrl ../include/CosNotifyComm_StructuredPullConsumer.hrl ../include/CosNotifyComm_StructuredPullSupplier.hrl ../include/CosNotifyComm_StructuredPushConsumer.hrl ../include/CosNotifyComm_StructuredPushSupplier.hrl ../include/oe_CosNotifyFilter.hrl ../include/CosNotifyFilter.hrl ../include/CosNotifyFilter_Filter.hrl ../include/CosNotifyFilter_FilterAdmin.hrl ../include/CosNotifyFilter_FilterFactory.hrl ../include/CosNotifyFilter_MappingFilter.hrl ../include/oe_CosNotifyChannelAdmin.hrl ../include/CosNotifyChannelAdmin.hrl ../include/CosNotifyChannelAdmin_ConsumerAdmin.hrl ../include/CosNotifyChannelAdmin_EventChannel.hrl ../include/CosNotifyChannelAdmin_EventChannelFactory.hrl ../include/CosNotifyChannelAdmin_ProxyConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_ProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_ProxySupplier.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_SupplierAdmin.hrl  oe_CosNotification.erl CosNotification.erl CosNotification_AdminPropertiesAdmin.erl CosNotification_EventHeader.erl CosNotification_EventType.erl CosNotification_FixedEventHeader.erl CosNotification_NamedPropertyRange.erl CosNotification_Property.erl CosNotification_PropertyError.erl CosNotification_PropertyRange.erl CosNotification_QoSAdmin.erl CosNotification_StructuredEvent.erl CosNotification_UnsupportedAdmin.erl CosNotification_UnsupportedQoS.erl CosNotification_EventBatch.erl CosNotification_EventTypeSeq.erl CosNotification_NamedPropertyRangeSeq.erl CosNotification_PropertyErrorSeq.erl CosNotification_PropertySeq.erl oe_cosNotificationAppComm.erl oe_CosNotificationComm_Event.erl oe_CosNotifyComm.erl CosNotifyComm_InvalidEventType.erl CosNotifyComm_NotifyPublish.erl CosNotifyComm_NotifySubscribe.erl CosNotifyComm_PullConsumer.erl CosNotifyComm_PullSupplier.erl CosNotifyComm_PushConsumer.erl CosNotifyComm_PushSupplier.erl CosNotifyComm_SequencePullConsumer.erl CosNotifyComm_SequencePullSupplier.erl CosNotifyComm_SequencePushConsumer.erl CosNotifyComm_SequencePushSupplier.erl CosNotifyComm_StructuredPullConsumer.erl CosNotifyComm_StructuredPullSupplier.erl CosNotifyComm_StructuredPushConsumer.erl CosNotifyComm_StructuredPushSupplier.erl  oe_CosNotifyFilter.erl CosNotifyFilter_CallbackNotFound.erl CosNotifyFilter_ConstraintExp.erl CosNotifyFilter_ConstraintInfo.erl CosNotifyFilter_ConstraintNotFound.erl CosNotifyFilter_DuplicateConstraintID.erl CosNotifyFilter_Filter.erl CosNotifyFilter_FilterAdmin.erl CosNotifyFilter_FilterFactory.erl CosNotifyFilter_FilterNotFound.erl CosNotifyFilter_InvalidConstraint.erl CosNotifyFilter_InvalidGrammar.erl CosNotifyFilter_InvalidValue.erl CosNotifyFilter_MappingConstraintInfo.erl CosNotifyFilter_MappingConstraintPair.erl CosNotifyFilter_MappingFilter.erl CosNotifyFilter_UnsupportedFilterableData.erl CosNotifyFilter_CallbackIDSeq.erl CosNotifyFilter_ConstraintExpSeq.erl CosNotifyFilter_ConstraintIDSeq.erl CosNotifyFilter_ConstraintInfoSeq.erl CosNotifyFilter_FilterIDSeq.erl CosNotifyFilter_MappingConstraintInfoSeq.erl CosNotifyFilter_MappingConstraintPairSeq.erl oe_CosNotifyChannelAdmin.erl CosNotifyChannelAdmin_AdminLimit.erl CosNotifyChannelAdmin_AdminLimitExceeded.erl CosNotifyChannelAdmin_AdminNotFound.erl CosNotifyChannelAdmin_ChannelNotFound.erl CosNotifyChannelAdmin_ConnectionAlreadyActive.erl CosNotifyChannelAdmin_ConnectionAlreadyInactive.erl CosNotifyChannelAdmin_ConsumerAdmin.erl CosNotifyChannelAdmin_EventChannel.erl CosNotifyChannelAdmin_EventChannelFactory.erl CosNotifyChannelAdmin_NotConnected.erl CosNotifyChannelAdmin_ProxyConsumer.erl CosNotifyChannelAdmin_ProxyNotFound.erl CosNotifyChannelAdmin_ProxyPullConsumer.erl CosNotifyChannelAdmin_ProxyPullSupplier.erl CosNotifyChannelAdmin_ProxyPushConsumer.erl CosNotifyChannelAdmin_ProxyPushSupplier.erl CosNotifyChannelAdmin_ProxySupplier.erl CosNotifyChannelAdmin_SequenceProxyPullConsumer.erl CosNotifyChannelAdmin_SequenceProxyPullSupplier.erl CosNotifyChannelAdmin_SequenceProxyPushConsumer.erl CosNotifyChannelAdmin_SequenceProxyPushSupplier.erl CosNotifyChannelAdmin_StructuredProxyPullConsumer.erl CosNotifyChannelAdmin_StructuredProxyPullSupplier.erl CosNotifyChannelAdmin_StructuredProxyPushConsumer.erl CosNotifyChannelAdmin_StructuredProxyPushSupplier.erl CosNotifyChannelAdmin_SupplierAdmin.erl CosNotifyChannelAdmin_AdminIDSeq.erl CosNotifyChannelAdmin_ChannelIDSeq.erl CosNotifyChannelAdmin_ProxyIDSeq.erl cosNotification_Grammar.erl CosNotification.idl CosNotifyChannelAdmin.idl CosNotifyFilter.idl CosNotifyComm.idl cosNotificationAppComm.idl cosNotification_Grammar.yrl "/usr/local/lib/erlang/lib/cosNotification-1.2.2/src"
/usr/bin/install -c -m 644 CosNotification_Common.erl CosNotifyChannelAdmin_ConsumerAdmin_impl.erl CosNotifyChannelAdmin_EventChannelFactory_impl.erl CosNotifyChannelAdmin_EventChannel_impl.erl CosNotifyChannelAdmin_SupplierAdmin_impl.erl CosNotifyFilter_Filter_impl.erl CosNotifyFilter_MappingFilter_impl.erl CosNotifyFilter_FilterFactory_impl.erl PullerConsumer_impl.erl PullerSupplier_impl.erl PusherConsumer_impl.erl PusherSupplier_impl.erl cosNotificationApp.erl cosNotification_Scanner.erl cosNotification_Filter.erl cosNotification_eventDB.erl  CosNotification_Definitions.hrl CosNotification.idl CosNotifyChannelAdmin.idl CosNotifyFilter.idl CosNotifyComm.idl cosNotificationAppComm.idl cosNotification_Grammar.yrl "/usr/local/lib/erlang/lib/cosNotification-1.2.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosNotification-1.2.2/include"
/usr/bin/install -c -m 644 ../include/oe_CosNotification.hrl ../include/CosNotification.hrl ../include/CosNotification_AdminPropertiesAdmin.hrl ../include/CosNotification_QoSAdmin.hrl oe_cosNotificationAppComm.hrl oe_CosNotificationComm.hrl oe_CosNotificationComm_Event.hrl ../include/oe_CosNotifyComm.hrl ../include/CosNotifyComm.hrl ../include/CosNotifyComm_NotifyPublish.hrl ../include/CosNotifyComm_NotifySubscribe.hrl ../include/CosNotifyComm_PullConsumer.hrl ../include/CosNotifyComm_PullSupplier.hrl ../include/CosNotifyComm_PushConsumer.hrl ../include/CosNotifyComm_PushSupplier.hrl ../include/CosNotifyComm_SequencePullConsumer.hrl ../include/CosNotifyComm_SequencePullSupplier.hrl ../include/CosNotifyComm_SequencePushConsumer.hrl ../include/CosNotifyComm_SequencePushSupplier.hrl ../include/CosNotifyComm_StructuredPullConsumer.hrl ../include/CosNotifyComm_StructuredPullSupplier.hrl ../include/CosNotifyComm_StructuredPushConsumer.hrl ../include/CosNotifyComm_StructuredPushSupplier.hrl ../include/oe_CosNotifyFilter.hrl ../include/CosNotifyFilter.hrl ../include/CosNotifyFilter_Filter.hrl ../include/CosNotifyFilter_FilterAdmin.hrl ../include/CosNotifyFilter_FilterFactory.hrl ../include/CosNotifyFilter_MappingFilter.hrl ../include/oe_CosNotifyChannelAdmin.hrl ../include/CosNotifyChannelAdmin.hrl ../include/CosNotifyChannelAdmin_ConsumerAdmin.hrl ../include/CosNotifyChannelAdmin_EventChannel.hrl ../include/CosNotifyChannelAdmin_EventChannelFactory.hrl ../include/CosNotifyChannelAdmin_ProxyConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_ProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_ProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_ProxySupplier.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_SequenceProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPullConsumer.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPullSupplier.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPushConsumer.hrl ../include/CosNotifyChannelAdmin_StructuredProxyPushSupplier.hrl ../include/CosNotifyChannelAdmin_SupplierAdmin.hrl  "/usr/local/lib/erlang/lib/cosNotification-1.2.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosNotification-1.2.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosNotification-1.2.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosNotification-1.2.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
=== Leaving application cosNotification
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
=== Entering application cosProperty
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosProperty-1.2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosProperty.beam ../ebin/CosPropertyService_ConflictingProperty.beam ../ebin/CosPropertyService_ConstraintNotSupported.beam ../ebin/CosPropertyService_FixedProperty.beam ../ebin/CosPropertyService_InvalidPropertyName.beam ../ebin/CosPropertyService_MultipleExceptions.beam ../ebin/CosPropertyService_Properties.beam ../ebin/CosPropertyService_PropertiesIterator.beam ../ebin/CosPropertyService_Property.beam ../ebin/CosPropertyService_PropertyDef.beam ../ebin/CosPropertyService_PropertyDefs.beam ../ebin/CosPropertyService_PropertyException.beam ../ebin/CosPropertyService_PropertyExceptions.beam ../ebin/CosPropertyService_PropertyMode.beam ../ebin/CosPropertyService_PropertyModes.beam ../ebin/CosPropertyService_PropertyNames.beam ../ebin/CosPropertyService_PropertyNamesIterator.beam ../ebin/CosPropertyService_PropertyNotFound.beam ../ebin/CosPropertyService_PropertySet.beam ../ebin/CosPropertyService_PropertySetDef.beam ../ebin/CosPropertyService_PropertySetDefFactory.beam ../ebin/CosPropertyService_PropertySetFactory.beam ../ebin/CosPropertyService_PropertyTypes.beam ../ebin/CosPropertyService_ReadOnlyProperty.beam ../ebin/CosPropertyService_UnsupportedMode.beam ../ebin/CosPropertyService_UnsupportedProperty.beam ../ebin/CosPropertyService_UnsupportedTypeCode.beam ../ebin/cosProperty.beam ../ebin/CosPropertyService_PropertySetDefFactory_impl.beam ../ebin/CosPropertyService_PropertySetDef_impl.beam ../ebin/CosPropertyService_PropertySetFactory_impl.beam ../ebin/CosPropertyService_PropertiesIterator_impl.beam ../ebin/CosPropertyService_PropertyNamesIterator_impl.beam  ../ebin/cosProperty.app ../ebin/cosProperty.appup "/usr/local/lib/erlang/lib/cosProperty-1.2.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosProperty-1.2.1/src"
/usr/bin/install -c -m 644 ../include/oe_CosProperty.hrl ../include/CosPropertyService.hrl ../include/CosPropertyService_PropertiesIterator.hrl ../include/CosPropertyService_PropertyNamesIterator.hrl ../include/CosPropertyService_PropertySet.hrl ../include/CosPropertyService_PropertySetDef.hrl ../include/CosPropertyService_PropertySetDefFactory.hrl ../include/CosPropertyService_PropertySetFactory.hrl oe_CosProperty.erl CosPropertyService_ConflictingProperty.erl CosPropertyService_ConstraintNotSupported.erl CosPropertyService_FixedProperty.erl CosPropertyService_InvalidPropertyName.erl CosPropertyService_MultipleExceptions.erl CosPropertyService_Properties.erl CosPropertyService_PropertiesIterator.erl CosPropertyService_Property.erl CosPropertyService_PropertyDef.erl CosPropertyService_PropertyDefs.erl CosPropertyService_PropertyException.erl CosPropertyService_PropertyExceptions.erl CosPropertyService_PropertyMode.erl CosPropertyService_PropertyModes.erl CosPropertyService_PropertyNames.erl CosPropertyService_PropertyNamesIterator.erl CosPropertyService_PropertyNotFound.erl CosPropertyService_PropertySet.erl CosPropertyService_PropertySetDef.erl CosPropertyService_PropertySetDefFactory.erl CosPropertyService_PropertySetFactory.erl CosPropertyService_PropertyTypes.erl CosPropertyService_ReadOnlyProperty.erl CosPropertyService_UnsupportedMode.erl CosPropertyService_UnsupportedProperty.erl CosPropertyService_UnsupportedTypeCode.erl CosProperty.idl "/usr/local/lib/erlang/lib/cosProperty-1.2.1/src"
/usr/bin/install -c -m 644 cosProperty.erl CosPropertyService_PropertySetDefFactory_impl.erl CosPropertyService_PropertySetDef_impl.erl CosPropertyService_PropertySetFactory_impl.erl CosPropertyService_PropertiesIterator_impl.erl CosPropertyService_PropertyNamesIterator_impl.erl  cosProperty.hrl  oe_CosProperty.erl CosPropertyService_ConflictingProperty.erl CosPropertyService_ConstraintNotSupported.erl CosPropertyService_FixedProperty.erl CosPropertyService_InvalidPropertyName.erl CosPropertyService_MultipleExceptions.erl CosPropertyService_Properties.erl CosPropertyService_PropertiesIterator.erl CosPropertyService_Property.erl CosPropertyService_PropertyDef.erl CosPropertyService_PropertyDefs.erl CosPropertyService_PropertyException.erl CosPropertyService_PropertyExceptions.erl CosPropertyService_PropertyMode.erl CosPropertyService_PropertyModes.erl CosPropertyService_PropertyNames.erl CosPropertyService_PropertyNamesIterator.erl CosPropertyService_PropertyNotFound.erl CosPropertyService_PropertySet.erl CosPropertyService_PropertySetDef.erl CosPropertyService_PropertySetDefFactory.erl CosPropertyService_PropertySetFactory.erl CosPropertyService_PropertyTypes.erl CosPropertyService_ReadOnlyProperty.erl CosPropertyService_UnsupportedMode.erl CosPropertyService_UnsupportedProperty.erl CosPropertyService_UnsupportedTypeCode.erl CosProperty.idl "/usr/local/lib/erlang/lib/cosProperty-1.2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosProperty-1.2.1/include"
/usr/bin/install -c -m 644 ../include/oe_CosProperty.hrl ../include/CosPropertyService.hrl ../include/CosPropertyService_PropertiesIterator.hrl ../include/CosPropertyService_PropertyNamesIterator.hrl ../include/CosPropertyService_PropertySet.hrl ../include/CosPropertyService_PropertySetDef.hrl ../include/CosPropertyService_PropertySetDefFactory.hrl ../include/CosPropertyService_PropertySetFactory.hrl "/usr/local/lib/erlang/lib/cosProperty-1.2.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosProperty-1.2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosProperty-1.2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosProperty-1.2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
=== Leaving application cosProperty
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
=== Entering application cosFileTransfer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosFileTransfer.beam ../ebin/CosFileTransfer.beam ../ebin/CosFileTransfer_AccessLevel.beam ../ebin/CosFileTransfer_CommandNotImplementedException.beam ../ebin/CosFileTransfer_Directory.beam ../ebin/CosFileTransfer_File.beam ../ebin/CosFileTransfer_FileIterator.beam ../ebin/CosFileTransfer_FileList.beam ../ebin/CosFileTransfer_FileNameList.beam ../ebin/CosFileTransfer_FileNotFoundException.beam ../ebin/CosFileTransfer_FileTransferSession.beam ../ebin/CosFileTransfer_FileWrapper.beam ../ebin/CosFileTransfer_IllegalOperationException.beam ../ebin/CosFileTransfer_ProtocolAddressList.beam ../ebin/CosFileTransfer_ProtocolSupport.beam ../ebin/CosFileTransfer_RequestFailureException.beam ../ebin/CosFileTransfer_SessionException.beam ../ebin/CosFileTransfer_SupportedProtocolAddresses.beam ../ebin/CosFileTransfer_TransferException.beam ../ebin/CosFileTransfer_VirtualFileSystem.beam ../ebin/CosFileTransfer_VirtualFileSystem_ContentList.beam ../ebin/cosFileTransferApp.beam ../ebin/CosFileTransfer_Directory_impl.beam ../ebin/CosFileTransfer_File_impl.beam ../ebin/CosFileTransfer_VirtualFileSystem_impl.beam ../ebin/CosFileTransfer_FileTransferSession_impl.beam ../ebin/CosFileTransfer_FileIterator_impl.beam ../ebin/cosFileTransferNATIVE_file.beam  ../ebin/cosFileTransfer.app ../ebin/cosFileTransfer.appup "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/src"
/usr/bin/install -c -m 644 ../include/oe_CosFileTransfer.hrl ../include/CosFileTransfer.hrl ../include/CosFileTransfer_Directory.hrl ../include/CosFileTransfer_File.hrl ../include/CosFileTransfer_FileIterator.hrl ../include/CosFileTransfer_FileTransferSession.hrl ../include/CosFileTransfer_VirtualFileSystem.hrl oe_CosFileTransfer.erl CosFileTransfer.erl CosFileTransfer_AccessLevel.erl CosFileTransfer_CommandNotImplementedException.erl CosFileTransfer_Directory.erl CosFileTransfer_File.erl CosFileTransfer_FileIterator.erl CosFileTransfer_FileList.erl CosFileTransfer_FileNameList.erl CosFileTransfer_FileNotFoundException.erl CosFileTransfer_FileTransferSession.erl CosFileTransfer_FileWrapper.erl CosFileTransfer_IllegalOperationException.erl CosFileTransfer_ProtocolAddressList.erl CosFileTransfer_ProtocolSupport.erl CosFileTransfer_RequestFailureException.erl CosFileTransfer_SessionException.erl CosFileTransfer_SupportedProtocolAddresses.erl CosFileTransfer_TransferException.erl CosFileTransfer_VirtualFileSystem.erl CosFileTransfer_VirtualFileSystem_ContentList.erl  CosFileTransfer.idl "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/src"
/usr/bin/install -c -m 644 cosFileTransferApp.erl CosFileTransfer_Directory_impl.erl CosFileTransfer_File_impl.erl CosFileTransfer_VirtualFileSystem_impl.erl CosFileTransfer_FileTransferSession_impl.erl CosFileTransfer_FileIterator_impl.erl cosFileTransferNATIVE_file.erl  cosFileTransferApp.hrl  oe_CosFileTransfer.erl CosFileTransfer.erl CosFileTransfer_AccessLevel.erl CosFileTransfer_CommandNotImplementedException.erl CosFileTransfer_Directory.erl CosFileTransfer_File.erl CosFileTransfer_FileIterator.erl CosFileTransfer_FileList.erl CosFileTransfer_FileNameList.erl CosFileTransfer_FileNotFoundException.erl CosFileTransfer_FileTransferSession.erl CosFileTransfer_FileWrapper.erl CosFileTransfer_IllegalOperationException.erl CosFileTransfer_ProtocolAddressList.erl CosFileTransfer_ProtocolSupport.erl CosFileTransfer_RequestFailureException.erl CosFileTransfer_SessionException.erl CosFileTransfer_SupportedProtocolAddresses.erl CosFileTransfer_TransferException.erl CosFileTransfer_VirtualFileSystem.erl CosFileTransfer_VirtualFileSystem_ContentList.erl  CosFileTransfer.idl "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/include"
/usr/bin/install -c -m 644 ../include/oe_CosFileTransfer.hrl ../include/CosFileTransfer.hrl ../include/CosFileTransfer_Directory.hrl ../include/CosFileTransfer_File.hrl ../include/CosFileTransfer_FileIterator.hrl ../include/CosFileTransfer_FileTransferSession.hrl ../include/CosFileTransfer_VirtualFileSystem.hrl "/usr/local/lib/erlang/lib/cosFileTransfer-1.2.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosFileTransfer-1.2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosFileTransfer-1.2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosFileTransfer-1.2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
=== Leaving application cosFileTransfer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
=== Entering application cosEventDomain
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1"
/usr/bin/install -c -m 644 ../info "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/ebin"
/usr/bin/install -c -m 644 ../ebin/oe_CosEventDomainAdmin.beam ../ebin/CosEventDomainAdmin.beam ../ebin/CosEventDomainAdmin_DiamondSeq.beam ../ebin/CosEventDomainAdmin_AlreadyExists.beam ../ebin/CosEventDomainAdmin_DomainIDSeq.beam ../ebin/CosEventDomainAdmin_Connection.beam ../ebin/CosEventDomainAdmin_ConnectionIDSeq.beam ../ebin/CosEventDomainAdmin_ConnectionNotFound.beam ../ebin/CosEventDomainAdmin_CycleCreationForbidden.beam ../ebin/CosEventDomainAdmin_CycleSeq.beam ../ebin/CosEventDomainAdmin_DiamondCreationForbidden.beam ../ebin/CosEventDomainAdmin_DomainNotFound.beam ../ebin/CosEventDomainAdmin_EventDomain.beam ../ebin/CosEventDomainAdmin_EventDomainFactory.beam ../ebin/CosEventDomainAdmin_MemberIDSeq.beam ../ebin/CosEventDomainAdmin_RouteSeq.beam ../ebin/CosEventDomainAdmin_EventDomainFactory_impl.beam ../ebin/CosEventDomainAdmin_EventDomain_impl.beam ../ebin/cosEventDomainApp.beam  ../ebin/cosEventDomain.app ../ebin/cosEventDomain.appup "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/src"
/usr/bin/install -c -m 644 CosEventDomainAdmin_EventDomainFactory_impl.erl CosEventDomainAdmin_EventDomain_impl.erl cosEventDomainApp.erl  cosEventDomainApp.hrl oe_CosEventDomainAdmin.erl CosEventDomainAdmin.erl CosEventDomainAdmin_DiamondSeq.erl CosEventDomainAdmin_AlreadyExists.erl CosEventDomainAdmin_DomainIDSeq.erl CosEventDomainAdmin_Connection.erl CosEventDomainAdmin_ConnectionIDSeq.erl CosEventDomainAdmin_ConnectionNotFound.erl CosEventDomainAdmin_CycleCreationForbidden.erl CosEventDomainAdmin_CycleSeq.erl CosEventDomainAdmin_DiamondCreationForbidden.erl CosEventDomainAdmin_DomainNotFound.erl CosEventDomainAdmin_EventDomain.erl CosEventDomainAdmin_EventDomainFactory.erl CosEventDomainAdmin_MemberIDSeq.erl CosEventDomainAdmin_RouteSeq.erl CosEventDomainAdmin.idl "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/include"
/usr/bin/install -c -m 644 ../include/oe_CosEventDomainAdmin.hrl ../include/CosEventDomainAdmin.hrl ../include/CosEventDomainAdmin_EventDomainFactory.hrl ../include/CosEventDomainAdmin_EventDomain.hrl "/usr/local/lib/erlang/lib/cosEventDomain-1.2.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "cosEventDomain-1.2.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep cosEventDomain-1.2.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo cosEventDomain-1.2.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
=== Leaving application cosEventDomain
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
=== Entering application et
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/et-1.6/ebin"
/usr/bin/install -c -m 644 ../ebin/et.beam ../ebin/et_collector.beam ../ebin/et_selector.beam ../ebin/et_viewer.beam ../ebin/et_wx_contents_viewer.beam ../ebin/et_wx_viewer.beam "/usr/local/lib/erlang/lib/et-1.6/ebin"
/usr/bin/install -c -m 644 ../ebin/et.app ../ebin/et.appup "/usr/local/lib/erlang/lib/et-1.6/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/et-1.6/src"
/usr/bin/install -c -m 644 et.erl et_collector.erl et_selector.erl et_viewer.erl et_wx_contents_viewer.erl et_wx_viewer.erl "/usr/local/lib/erlang/lib/et-1.6/src"
/usr/bin/install -c -m 644 et_internal.hrl "/usr/local/lib/erlang/lib/et-1.6/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/et-1.6/include"
/usr/bin/install -c -m 644 ../include/et.hrl "/usr/local/lib/erlang/lib/et-1.6/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/et-1.6/examples"
/usr/bin/install -c -m 644 et_demo.erl et_display_demo.erl et_trace_demo.erl   "/usr/local/lib/erlang/lib/et-1.6/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "et-1.6" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep et-1.6 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo et-1.6 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
=== Leaving application et
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
=== Entering application megaco
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco.app ../../ebin/megaco.appup "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/app"
/usr/bin/install -c -m 644 megaco.erl	 megaco_internal.hrl "/usr/local/lib/erlang/lib/megaco-3.18.1/src/app"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/include"
/usr/bin/install -c -m 644 ../../include/megaco.hrl ../../include/megaco_message_v1.hrl ../../include/megaco_message_v2.hrl ../../include/megaco_message_prev3a.hrl ../../include/megaco_message_prev3b.hrl ../../include/megaco_message_prev3c.hrl ../../include/megaco_message_v3.hrl ../../include/megaco_sdp.hrl "/usr/local/lib/erlang/lib/megaco-3.18.1/include"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco_edist_compress.beam ../../ebin/megaco_encoder.beam ../../ebin/megaco_transport.beam ../../ebin/megaco_config_misc.beam ../../ebin/megaco_config.beam ../../ebin/megaco_digit_map.beam ../../ebin/megaco_erl_dist_encoder.beam ../../ebin/megaco_erl_dist_encoder_mc.beam ../../ebin/megaco_filter.beam ../../ebin/megaco_messenger.beam ../../ebin/megaco_messenger_misc.beam ../../ebin/megaco_misc_sup.beam ../../ebin/megaco_monitor.beam ../../ebin/megaco_sdp.beam ../../ebin/megaco_sup.beam ../../ebin/megaco_stats.beam ../../ebin/megaco_timer.beam ../../ebin/megaco_trans_sender.beam ../../ebin/megaco_trans_sup.beam ../../ebin/megaco_user_default.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/engine"
/usr/bin/install -c -m 644 megaco_config_misc.erl megaco_config.erl megaco_digit_map.erl megaco_erl_dist_encoder.erl megaco_erl_dist_encoder_mc.erl megaco_filter.erl megaco_messenger.erl megaco_messenger_misc.erl megaco_misc_sup.erl megaco_monitor.erl megaco_sdp.erl megaco_sup.erl megaco_stats.erl megaco_timer.erl megaco_trans_sender.erl megaco_trans_sup.erl megaco_user_default.erl megaco_edist_compress.erl megaco_encoder.erl megaco_transport.erl megaco_message_internal.hrl "/usr/local/lib/erlang/lib/megaco-3.18.1/src/engine"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/include"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco_text_parser_v1.beam ../../ebin/megaco_text_parser_v2.beam ../../ebin/megaco_text_parser_v3.beam ../../ebin/megaco_text_parser_prev3a.beam ../../ebin/megaco_text_parser_prev3b.beam ../../ebin/megaco_text_parser_prev3c.beam ../../ebin/megaco_text_mini_parser.beam ../../ebin/megaco_compact_text_encoder.beam ../../ebin/megaco_compact_text_encoder_v1.beam ../../ebin/megaco_compact_text_encoder_v2.beam ../../ebin/megaco_compact_text_encoder_v3.beam ../../ebin/megaco_compact_text_encoder_prev3a.beam ../../ebin/megaco_compact_text_encoder_prev3b.beam ../../ebin/megaco_compact_text_encoder_prev3c.beam ../../ebin/megaco_pretty_text_encoder.beam ../../ebin/megaco_pretty_text_encoder_v1.beam ../../ebin/megaco_pretty_text_encoder_v2.beam ../../ebin/megaco_pretty_text_encoder_v3.beam ../../ebin/megaco_pretty_text_encoder_prev3a.beam ../../ebin/megaco_pretty_text_encoder_prev3b.beam ../../ebin/megaco_pretty_text_encoder_prev3c.beam ../../ebin/megaco_text_mini_decoder.beam ../../ebin/megaco_text_scanner.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/text"
/usr/bin/install -c -m 644 megaco_compact_text_encoder.erl megaco_compact_text_encoder_v1.erl megaco_compact_text_encoder_v2.erl megaco_compact_text_encoder_v3.erl megaco_compact_text_encoder_prev3a.erl megaco_compact_text_encoder_prev3b.erl megaco_compact_text_encoder_prev3c.erl megaco_pretty_text_encoder.erl megaco_pretty_text_encoder_v1.erl megaco_pretty_text_encoder_v2.erl megaco_pretty_text_encoder_v3.erl megaco_pretty_text_encoder_prev3a.erl megaco_pretty_text_encoder_prev3b.erl megaco_pretty_text_encoder_prev3c.erl megaco_text_mini_decoder.erl megaco_text_scanner.erl megaco_text_parser_v1.erl megaco_text_parser_v2.erl megaco_text_parser_v3.erl megaco_text_parser_prev3a.erl megaco_text_parser_prev3b.erl megaco_text_parser_prev3c.erl megaco_text_mini_parser.erl megaco_text_parser_v1.yrl megaco_text_parser_v2.yrl megaco_text_parser_v3.yrl megaco_text_parser_prev3a.yrl megaco_text_parser_prev3b.yrl megaco_text_parser_prev3c.yrl megaco_text_mini_parser.yrl megaco_text_gen_v1.hrl megaco_text_gen_v2.hrl megaco_text_gen_v3.hrl megaco_text_gen_prev3a.hrl megaco_text_gen_prev3b.hrl megaco_text_gen_prev3c.hrl megaco_text_parser_v1.hrl megaco_text_parser_v2.hrl megaco_text_parser_v3.hrl megaco_text_parser_prev3a.hrl megaco_text_parser_prev3b.hrl megaco_text_parser_prev3c.hrl megaco_text_mini_parser.hrl megaco_text_tokens.hrl  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/text"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
 MAKE	release
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[6]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
 MAKE	release_spec
make[7]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/flex"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/priv/lib"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/include"
/usr/bin/install -c -m 644 megaco_flex_scanner.erl megaco_flex_scanner_handler.erl	  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/flex"
/usr/bin/install -c -m 644 ../../ebin/megaco_flex_scanner.beam ../../ebin/megaco_flex_scanner_handler.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
make[7]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[6]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco_binary_encoder.beam ../../ebin/megaco_binary_encoder_lib.beam ../../ebin/megaco_ber_encoder.beam ../../ebin/megaco_ber_media_gateway_control_v1.beam ../../ebin/megaco_ber_media_gateway_control_v2.beam ../../ebin/megaco_ber_media_gateway_control_prev3a.beam ../../ebin/megaco_ber_media_gateway_control_prev3b.beam ../../ebin/megaco_ber_media_gateway_control_prev3c.beam ../../ebin/megaco_ber_media_gateway_control_v3.beam ../../ebin/megaco_per_encoder.beam ../../ebin/megaco_per_media_gateway_control_v1.beam ../../ebin/megaco_per_media_gateway_control_v2.beam ../../ebin/megaco_per_media_gateway_control_prev3a.beam ../../ebin/megaco_per_media_gateway_control_prev3b.beam ../../ebin/megaco_per_media_gateway_control_prev3c.beam ../../ebin/megaco_per_media_gateway_control_v3.beam ../../ebin/megaco_binary_name_resolver_v1.beam ../../ebin/megaco_binary_name_resolver_v2.beam ../../ebin/megaco_binary_name_resolver_prev3a.beam ../../ebin/megaco_binary_name_resolver_prev3b.beam ../../ebin/megaco_binary_name_resolver_prev3c.beam ../../ebin/megaco_binary_name_resolver_v3.beam ../../ebin/megaco_binary_term_id.beam ../../ebin/megaco_binary_term_id_gen.beam ../../ebin/megaco_binary_transformer_v1.beam ../../ebin/megaco_binary_transformer_v2.beam ../../ebin/megaco_binary_transformer_prev3a.beam ../../ebin/megaco_binary_transformer_prev3b.beam ../../ebin/megaco_binary_transformer_prev3c.beam ../../ebin/megaco_binary_transformer_v3.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/binary"
/usr/bin/install -c -m 644 megaco_binary_encoder.erl megaco_binary_encoder_lib.erl megaco_ber_encoder.erl megaco_ber_media_gateway_control_v1.erl megaco_ber_media_gateway_control_v2.erl megaco_ber_media_gateway_control_prev3a.erl megaco_ber_media_gateway_control_prev3b.erl megaco_ber_media_gateway_control_prev3c.erl megaco_ber_media_gateway_control_v3.erl megaco_per_encoder.erl megaco_per_media_gateway_control_v1.erl megaco_per_media_gateway_control_v2.erl megaco_per_media_gateway_control_prev3a.erl megaco_per_media_gateway_control_prev3b.erl megaco_per_media_gateway_control_prev3c.erl megaco_per_media_gateway_control_v3.erl megaco_binary_name_resolver_v1.erl megaco_binary_name_resolver_v2.erl megaco_binary_name_resolver_prev3a.erl megaco_binary_name_resolver_prev3b.erl megaco_binary_name_resolver_prev3c.erl megaco_binary_name_resolver_v3.erl megaco_binary_term_id.erl megaco_binary_term_id_gen.erl megaco_binary_transformer_v1.erl megaco_binary_transformer_v2.erl megaco_binary_transformer_prev3a.erl megaco_binary_transformer_prev3b.erl megaco_binary_transformer_prev3c.erl megaco_binary_transformer_v3.erl	  megaco_ber_media_gateway_control_v1.hrl megaco_per_media_gateway_control_v1.hrl megaco_ber_media_gateway_control_v2.hrl megaco_per_media_gateway_control_v2.hrl megaco_ber_media_gateway_control_v3.hrl megaco_per_media_gateway_control_v3.hrl megaco_ber_media_gateway_control_prev3a.hrl megaco_per_media_gateway_control_prev3a.hrl megaco_ber_media_gateway_control_prev3b.hrl megaco_per_media_gateway_control_prev3b.hrl megaco_ber_media_gateway_control_prev3c.hrl megaco_per_media_gateway_control_prev3c.hrl MEDIA-GATEWAY-CONTROL-v1.asn MEDIA-GATEWAY-CONTROL-v2.asn MEDIA-GATEWAY-CONTROL-prev3a.asn "/usr/local/lib/erlang/lib/megaco-3.18.1/src/binary"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco_tcp.beam ../../ebin/megaco_tcp_sup.beam ../../ebin/megaco_tcp_accept.beam ../../ebin/megaco_tcp_accept_sup.beam ../../ebin/megaco_tcp_connection.beam ../../ebin/megaco_tcp_connection_sup.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/tcp"
/usr/bin/install -c -m 644 megaco_tcp.erl megaco_tcp_sup.erl megaco_tcp_accept.erl megaco_tcp_accept_sup.erl megaco_tcp_connection.erl megaco_tcp_connection_sup.erl	 megaco_tcp.hrl "/usr/local/lib/erlang/lib/megaco-3.18.1/src/tcp"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -m 644 ../../ebin/megaco_udp.beam ../../ebin/megaco_udp_sup.beam ../../ebin/megaco_udp_server.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/ebin"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/src/udp"
/usr/bin/install -c -m 644 megaco_udp.erl megaco_udp_sup.erl megaco_udp_server.erl	 megaco_udp.hrl "/usr/local/lib/erlang/lib/megaco-3.18.1/src/udp"
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/megaco-3.18.1/examples"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/simple"
/usr/bin/install -c -m 644 megaco_simple_mg.erl megaco_simple_mgc.erl	 ./megaco_simple_mg.beam ./megaco_simple_mgc.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/simple"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/examples"
/usr/bin/install -c -d  "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/meas"
/usr/bin/install -c -m 644 time_test.msgs "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/meas"
/usr/bin/install -c -m 644 meas.sh.skel mstone1.sh.skel "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/meas"
/usr/bin/install -c -m 644 meas.sh.skel mstone1.sh.skel ./megaco_codec_transform.beam ./megaco_codec_mstone_lib.beam ./megaco_codec_mstone1.beam ./megaco_codec_mstone2.beam ./megaco_codec_meas.beam "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/meas"
/usr/bin/install -c -m 644 megaco_codec_transform.erl megaco_codec_mstone_lib.erl megaco_codec_mstone1.erl megaco_codec_mstone2.erl megaco_codec_meas.erl "/usr/local/lib/erlang/lib/megaco-3.18.1/examples/meas"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "megaco-3.18.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep megaco-3.18.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo megaco-3.18.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
=== Leaving application megaco
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
=== Entering application eunit
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eunit-2.3.1/ebin"
/usr/bin/install -c -m 644 ../ebin/eunit_autoexport.beam ../ebin/eunit_striptests.beam ../ebin/eunit.beam ../ebin/eunit_tests.beam ../ebin/eunit_server.beam ../ebin/eunit_proc.beam ../ebin/eunit_serial.beam ../ebin/eunit_test.beam ../ebin/eunit_lib.beam ../ebin/eunit_data.beam ../ebin/eunit_tty.beam ../ebin/eunit_surefire.beam ../ebin/eunit_listener.beam ../ebin/eunit.app ../ebin/eunit.appup "/usr/local/lib/erlang/lib/eunit-2.3.1/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eunit-2.3.1/src"
/usr/bin/install -c -m 644 eunit_autoexport.erl eunit_striptests.erl eunit.erl eunit_tests.erl eunit_server.erl eunit_proc.erl eunit_serial.erl eunit_test.erl eunit_lib.erl eunit_data.erl eunit_tty.erl eunit_surefire.erl  "/usr/local/lib/erlang/lib/eunit-2.3.1/src"
/usr/bin/install -c -m 644 eunit_internal.hrl "/usr/local/lib/erlang/lib/eunit-2.3.1/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eunit-2.3.1/include"
/usr/bin/install -c -m 644 ../include/eunit.hrl "/usr/local/lib/erlang/lib/eunit-2.3.1/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eunit-2.3.1/examples"
/usr/bin/install -c -m 644 fib.erl tests.txt "/usr/local/lib/erlang/lib/eunit-2.3.1/examples"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "eunit-2.3.1" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep eunit-2.3.1 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo eunit-2.3.1 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
=== Leaving application eunit
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
=== Entering application ssh
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssh-4.3.2/src"
/usr/bin/install -c -m 644 ssh_auth.hrl ssh_connect.hrl ssh_transport.hrl ssh.hrl ssh_userauth.hrl ssh_xfer.hrl ssh.erl ssh_sup.erl sshc_sup.erl sshd_sup.erl ssh_connection_sup.erl ssh_connection.erl ssh_connection_handler.erl ssh_dbg.erl ssh_shell.erl ssh_system_sup.erl ssh_subsystem_sup.erl ssh_channel_sup.erl ssh_acceptor_sup.erl ssh_acceptor.erl ssh_app.erl ssh_auth.erl ssh_bits.erl ssh_cli.erl ssh_file.erl ssh_io.erl ssh_info.erl ssh_message.erl ssh_no_io.erl ssh_sftp.erl ssh_sftpd.erl ssh_sftpd_file.erl ssh_transport.erl ssh_xfer.erl ssh_sftpd_file_api.erl ssh_channel.erl ssh_daemon_channel.erl ssh_client_key_api.erl ssh_server_key_api.erl "/usr/local/lib/erlang/lib/ssh-4.3.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssh-4.3.2/ebin"
/usr/bin/install -c -m 644 ../ebin/ssh_sftpd_file_api.beam ../ebin/ssh_channel.beam ../ebin/ssh_daemon_channel.beam ../ebin/ssh_client_key_api.beam ../ebin/ssh_server_key_api.beam ../ebin/ssh.beam ../ebin/ssh_sup.beam ../ebin/sshc_sup.beam ../ebin/sshd_sup.beam ../ebin/ssh_connection_sup.beam ../ebin/ssh_connection.beam ../ebin/ssh_connection_handler.beam ../ebin/ssh_dbg.beam ../ebin/ssh_shell.beam ../ebin/ssh_system_sup.beam ../ebin/ssh_subsystem_sup.beam ../ebin/ssh_channel_sup.beam ../ebin/ssh_acceptor_sup.beam ../ebin/ssh_acceptor.beam ../ebin/ssh_app.beam ../ebin/ssh_auth.beam ../ebin/ssh_bits.beam ../ebin/ssh_cli.beam ../ebin/ssh_file.beam ../ebin/ssh_io.beam ../ebin/ssh_info.beam ../ebin/ssh_message.beam ../ebin/ssh_no_io.beam ../ebin/ssh_sftp.beam ../ebin/ssh_sftpd.beam ../ebin/ssh_sftpd_file.beam ../ebin/ssh_transport.beam ../ebin/ssh_xfer.beam ../ebin/ssh.app \
	../ebin/ssh.appup "/usr/local/lib/erlang/lib/ssh-4.3.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/ssh-4.3.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "ssh-4.3.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep ssh-4.3.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo ssh-4.3.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
=== Leaving application ssh
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
=== Entering application typer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/typer-0.9.11/src"
/usr/bin/install -c -m 644 typer.erl   \
		"/usr/local/lib/erlang/lib/typer-0.9.11/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/typer-0.9.11/ebin"
/usr/bin/install -c -m 644 ../ebin/typer.beam ../ebin/typer.app ../ebin/typer.appup "/usr/local/lib/erlang/lib/typer-0.9.11/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "typer-0.9.11" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep typer-0.9.11 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo typer-0.9.11 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
=== Leaving application typer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
=== Entering application percept
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/src"
/usr/bin/install -c -m 644 egd.erl egd_png.erl egd_font.erl egd_render.erl egd_primitives.erl percept.erl percept_db.erl percept_html.erl percept_image.erl percept_graph.erl percept_analyzer.erl "/usr/local/lib/erlang/lib/percept-0.9/src"
/usr/bin/install -c -m 644 egd.hrl percept.hrl "/usr/local/lib/erlang/lib/percept-0.9/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/ebin"
/usr/bin/install -c -m 644 ../ebin/egd.beam ../ebin/egd_png.beam ../ebin/egd_font.beam ../ebin/egd_render.beam ../ebin/egd_primitives.beam ../ebin/percept.beam ../ebin/percept_db.beam ../ebin/percept_html.beam ../ebin/percept_image.beam ../ebin/percept_graph.beam ../ebin/percept_analyzer.beam ../ebin/percept.app ../ebin/percept.appup "/usr/local/lib/erlang/lib/percept-0.9/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
# Finished
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/logs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/htdocs"
/usr/bin/install -c -m 644 server_root/htdocs/index.html "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/htdocs"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/conf"
/usr/bin/install -c -m 644 server_root/conf/mime.types  "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/conf"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/scripts"
/usr/bin/install -c -m 644 server_root/scripts/percept_area_select.js server_root/scripts/percept_error_handler.js server_root/scripts/percept_select_all.js "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/scripts"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/css"
/usr/bin/install -c -m 644 server_root/css/percept.css	 "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/css"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/images"
/usr/bin/install -c -m 644 server_root/images/nav.png server_root/images/white.png "/usr/local/lib/erlang/lib/percept-0.9/priv/server_root/images"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/percept-0.9/priv/fonts"
/usr/bin/install -c -m 644 fonts/6x11_latin1.wingsfont "/usr/local/lib/erlang/lib/percept-0.9/priv/fonts"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "percept-0.9" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep percept-0.9 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo percept-0.9 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
=== Leaving application percept
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
=== Entering application eldap
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eldap-1.2.2/ebin"
/usr/bin/install -c -m 644 ../ebin/ELDAPv3.hrl ../ebin/eldap.beam ../ebin/ELDAPv3.beam ../ebin/eldap.app ../ebin/eldap.appup "/usr/local/lib/erlang/lib/eldap-1.2.2/ebin"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eldap-1.2.2/src"
/usr/bin/install -c -m 644 eldap.erl "/usr/local/lib/erlang/lib/eldap-1.2.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eldap-1.2.2/asn1"
/usr/bin/install -c -m 644 ../asn1/ELDAPv3.asn1 "/usr/local/lib/erlang/lib/eldap-1.2.2/asn1"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/eldap-1.2.2/include"
/usr/bin/install -c -m 644 ../include/eldap.hrl "/usr/local/lib/erlang/lib/eldap-1.2.2/include"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "eldap-1.2.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep eldap-1.2.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo eldap-1.2.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
=== Leaving application eldap
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
=== Entering application dialyzer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/dialyzer-3.0.2/src"
/usr/bin/install -c -m 644 dialyzer.erl dialyzer_analysis_callgraph.erl dialyzer_behaviours.erl dialyzer_callgraph.erl dialyzer_cl.erl dialyzer_cl_parse.erl dialyzer_codeserver.erl dialyzer_contracts.erl dialyzer_dataflow.erl dialyzer_dep.erl dialyzer_explanation.erl dialyzer_gui_wx.erl dialyzer_options.erl dialyzer_plt.erl dialyzer_race_data_server.erl dialyzer_races.erl dialyzer_succ_typings.erl dialyzer_timing.erl dialyzer_typesig.erl dialyzer_coordinator.erl dialyzer_worker.erl dialyzer_utils.erl dialyzer.hrl dialyzer_gui_wx.hrl  \
		"/usr/local/lib/erlang/lib/dialyzer-3.0.2/src"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/dialyzer-3.0.2/ebin"
/usr/bin/install -c -m 644 ../ebin/dialyzer.beam ../ebin/dialyzer_analysis_callgraph.beam ../ebin/dialyzer_behaviours.beam ../ebin/dialyzer_callgraph.beam ../ebin/dialyzer_cl.beam ../ebin/dialyzer_cl_parse.beam ../ebin/dialyzer_codeserver.beam ../ebin/dialyzer_contracts.beam ../ebin/dialyzer_dataflow.beam ../ebin/dialyzer_dep.beam ../ebin/dialyzer_explanation.beam ../ebin/dialyzer_gui_wx.beam ../ebin/dialyzer_options.beam ../ebin/dialyzer_plt.beam ../ebin/dialyzer_race_data_server.beam ../ebin/dialyzer_races.beam ../ebin/dialyzer_succ_typings.beam ../ebin/dialyzer_timing.beam ../ebin/dialyzer_typesig.beam ../ebin/dialyzer_coordinator.beam ../ebin/dialyzer_worker.beam ../ebin/dialyzer_utils.beam ../ebin/dialyzer.app ../ebin/dialyzer.appup "/usr/local/lib/erlang/lib/dialyzer-3.0.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "dialyzer-3.0.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep dialyzer-3.0.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo dialyzer-3.0.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
=== Leaving application dialyzer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
Makefile:72: warning: overriding commands for target `clean'
/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/make/otp_subdir.mk:29: warning: ignoring old commands for target `clean'
=== Entering application hipe
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/rtl"
/usr/bin/install -c -m 644 hipe_rtl.erl hipe_rtl_cfg.erl hipe_rtl_liveness.erl hipe_icode2rtl.erl hipe_rtl_mk_switch.erl hipe_rtl_primops.erl hipe_rtl_varmap.erl hipe_rtl_exceptions.erl hipe_rtl_binary_match.erl hipe_rtl_binary_construct.erl hipe_rtl_arith_32.erl hipe_rtl_arith_64.erl hipe_rtl_ssa.erl hipe_rtl_ssa_const_prop.erl hipe_rtl_cleanup_const.erl hipe_rtl_symbolic.erl hipe_rtl_lcm.erl hipe_rtl_ssapre.erl hipe_rtl_binary.erl hipe_rtl_ssa_avail_expr.erl hipe_rtl_arch.erl hipe_tagscheme.erl hipe_literals.hrl "/usr/local/lib/erlang/lib/hipe-3.15.2/rtl"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_rtl.beam ../ebin/hipe_rtl_cfg.beam ../ebin/hipe_rtl_liveness.beam ../ebin/hipe_icode2rtl.beam ../ebin/hipe_rtl_mk_switch.beam ../ebin/hipe_rtl_primops.beam ../ebin/hipe_rtl_varmap.beam ../ebin/hipe_rtl_exceptions.beam ../ebin/hipe_rtl_binary_match.beam ../ebin/hipe_rtl_binary_construct.beam ../ebin/hipe_rtl_arith_32.beam ../ebin/hipe_rtl_arith_64.beam ../ebin/hipe_rtl_ssa.beam ../ebin/hipe_rtl_ssa_const_prop.beam ../ebin/hipe_rtl_cleanup_const.beam ../ebin/hipe_rtl_symbolic.beam ../ebin/hipe_rtl_lcm.beam ../ebin/hipe_rtl_ssapre.beam ../ebin/hipe_rtl_binary.beam ../ebin/hipe_rtl_ssa_avail_expr.beam ../ebin/hipe_rtl_arch.beam ../ebin/hipe_tagscheme.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/misc"
/usr/bin/install -c -m 644 hipe_consttab.erl hipe_gensym.erl hipe_data_pp.erl hipe_pack_constants.erl hipe_sdi.erl hipe_sdi.hrl "/usr/local/lib/erlang/lib/hipe-3.15.2/misc"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_consttab.beam ../ebin/hipe_gensym.beam ../ebin/hipe_data_pp.beam ../ebin/hipe_pack_constants.beam ../ebin/hipe_sdi.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
/usr/bin/install -c -m 644 ../vsn.mk "/usr/local/lib/erlang/lib/hipe-3.15.2"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/main"
/usr/bin/install -c -m 644 hipe_main.erl hipe.erl hipe.hrl "/usr/local/lib/erlang/lib/hipe-3.15.2/main"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_main.beam ../ebin/hipe.beam ../ebin/hipe.app ../ebin/hipe.appup "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/cerl"
/usr/bin/install -c -m 644 cerl_cconv.erl cerl_closurean.erl cerl_hipeify.erl cerl_lib.erl cerl_messagean.erl cerl_pmatch.erl cerl_prettypr.erl cerl_to_icode.erl cerl_typean.erl erl_bif_types.erl erl_types.erl cerl_hipe_primops.hrl "/usr/local/lib/erlang/lib/hipe-3.15.2/cerl"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/cerl_cconv.beam ../ebin/cerl_closurean.beam ../ebin/cerl_hipeify.beam ../ebin/cerl_lib.beam ../ebin/cerl_messagean.beam ../ebin/cerl_pmatch.beam ../ebin/cerl_prettypr.beam ../ebin/cerl_to_icode.beam ../ebin/cerl_typean.beam ../ebin/erl_bif_types.beam ../ebin/erl_types.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/icode"
/usr/bin/install -c -m 644 hipe_beam_to_icode.erl hipe_icode.erl hipe_icode_bincomp.erl hipe_icode_callgraph.erl hipe_icode_cfg.erl hipe_icode_coordinator.erl hipe_icode_fp.erl hipe_icode_exceptions.erl hipe_icode_inline_bifs.erl hipe_icode_instruction_counter.erl hipe_icode_liveness.erl hipe_icode_pp.erl hipe_icode_primops.erl hipe_icode_range.erl hipe_icode_split_arith.erl hipe_icode_ssa.erl hipe_icode_ssa_const_prop.erl hipe_icode_call_elim.erl hipe_icode_ssa_copy_prop.erl hipe_icode_ssa_struct_reuse.erl hipe_icode_type.erl hipe_icode_heap_test.erl hipe_icode_ebb.erl hipe_icode_mulret.erl hipe_icode.hrl hipe_icode_primops.hrl hipe_icode_type.hrl "/usr/local/lib/erlang/lib/hipe-3.15.2/icode"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_beam_to_icode.beam ../ebin/hipe_icode.beam ../ebin/hipe_icode_bincomp.beam ../ebin/hipe_icode_callgraph.beam ../ebin/hipe_icode_cfg.beam ../ebin/hipe_icode_coordinator.beam ../ebin/hipe_icode_fp.beam ../ebin/hipe_icode_exceptions.beam ../ebin/hipe_icode_inline_bifs.beam ../ebin/hipe_icode_instruction_counter.beam ../ebin/hipe_icode_liveness.beam ../ebin/hipe_icode_pp.beam ../ebin/hipe_icode_primops.beam ../ebin/hipe_icode_range.beam ../ebin/hipe_icode_split_arith.beam ../ebin/hipe_icode_ssa.beam ../ebin/hipe_icode_ssa_const_prop.beam ../ebin/hipe_icode_call_elim.beam ../ebin/hipe_icode_ssa_copy_prop.beam ../ebin/hipe_icode_ssa_struct_reuse.beam ../ebin/hipe_icode_type.beam ../ebin/hipe_icode_heap_test.beam ../ebin/hipe_icode_ebb.beam ../ebin/hipe_icode_mulret.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/flow"
/usr/bin/install -c -m 644 hipe_bb.erl hipe_dominators.erl hipe_gen_cfg.erl  cfg.inc ebb.inc liveness.inc "/usr/local/lib/erlang/lib/hipe-3.15.2/flow"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_bb.beam ../ebin/hipe_dominators.beam ../ebin/hipe_gen_cfg.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/util"
/usr/bin/install -c -m 644 hipe_timing.erl hipe_dot.erl hipe_digraph.erl hipe_vectors.erl  "/usr/local/lib/erlang/lib/hipe-3.15.2/util"
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_timing.beam ../ebin/hipe_dot.beam ../ebin/hipe_digraph.beam ../ebin/hipe_vectors.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[4]: Nothing to be done for `release_spec'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_ig.beam ../ebin/hipe_ig_moves.beam ../ebin/hipe_moves.beam ../ebin/hipe_node_sets.beam ../ebin/hipe_spillcost.beam ../ebin/hipe_reg_worklists.beam ../ebin/hipe_adj_list.beam ../ebin/hipe_temp_map.beam ../ebin/hipe_optimistic_regalloc.beam ../ebin/hipe_coalescing_regalloc.beam ../ebin/hipe_graph_coloring_regalloc.beam ../ebin/hipe_regalloc_loop.beam ../ebin/hipe_ls_regalloc.beam ../ebin/hipe_ppc_specific.beam ../ebin/hipe_ppc_specific_fp.beam ../ebin/hipe_sparc_specific.beam ../ebin/hipe_sparc_specific_fp.beam ../ebin/hipe_arm_specific.beam ../ebin/hipe_x86_specific.beam ../ebin/hipe_x86_specific_x87.beam ../ebin/hipe_amd64_specific.beam ../ebin/hipe_amd64_specific_sse2.beam ../ebin/hipe_amd64_specific_x87.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_rtl_to_sparc.beam ../ebin/hipe_sparc.beam ../ebin/hipe_sparc_assemble.beam ../ebin/hipe_sparc_cfg.beam ../ebin/hipe_sparc_defuse.beam ../ebin/hipe_sparc_encode.beam ../ebin/hipe_sparc_finalise.beam ../ebin/hipe_sparc_frame.beam ../ebin/hipe_sparc_liveness_all.beam ../ebin/hipe_sparc_liveness_fpr.beam ../ebin/hipe_sparc_liveness_gpr.beam ../ebin/hipe_sparc_main.beam ../ebin/hipe_sparc_pp.beam ../ebin/hipe_sparc_ra.beam ../ebin/hipe_sparc_ra_finalise.beam ../ebin/hipe_sparc_ra_ls.beam ../ebin/hipe_sparc_ra_naive.beam ../ebin/hipe_sparc_ra_postconditions.beam ../ebin/hipe_sparc_ra_postconditions_fp.beam ../ebin/hipe_sparc_registers.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_ppc.beam ../ebin/hipe_ppc_assemble.beam ../ebin/hipe_ppc_cfg.beam ../ebin/hipe_ppc_defuse.beam ../ebin/hipe_ppc_encode.beam ../ebin/hipe_ppc_finalise.beam ../ebin/hipe_ppc_frame.beam ../ebin/hipe_ppc_liveness_all.beam ../ebin/hipe_ppc_liveness_fpr.beam ../ebin/hipe_ppc_liveness_gpr.beam ../ebin/hipe_ppc_main.beam ../ebin/hipe_ppc_pp.beam ../ebin/hipe_ppc_ra.beam ../ebin/hipe_ppc_ra_finalise.beam ../ebin/hipe_ppc_ra_ls.beam ../ebin/hipe_ppc_ra_naive.beam ../ebin/hipe_ppc_ra_postconditions.beam ../ebin/hipe_ppc_ra_postconditions_fp.beam ../ebin/hipe_ppc_registers.beam ../ebin/hipe_rtl_to_ppc.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_rtl_to_x86.beam ../ebin/hipe_x86.beam ../ebin/hipe_x86_assemble.beam ../ebin/hipe_x86_cfg.beam ../ebin/hipe_x86_defuse.beam ../ebin/hipe_x86_encode.beam ../ebin/hipe_x86_frame.beam ../ebin/hipe_x86_liveness.beam ../ebin/hipe_x86_main.beam ../ebin/hipe_x86_postpass.beam ../ebin/hipe_x86_pp.beam ../ebin/hipe_x86_ra.beam ../ebin/hipe_x86_ra_finalise.beam ../ebin/hipe_x86_ra_ls.beam ../ebin/hipe_x86_ra_naive.beam ../ebin/hipe_x86_ra_postconditions.beam ../ebin/hipe_x86_ra_x87_ls.beam ../ebin/hipe_x86_registers.beam ../ebin/hipe_x86_spill_restore.beam ../ebin/hipe_x86_x87.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_amd64_assemble.beam ../ebin/hipe_amd64_defuse.beam ../ebin/hipe_amd64_encode.beam ../ebin/hipe_amd64_frame.beam ../ebin/hipe_amd64_liveness.beam ../ebin/hipe_amd64_main.beam ../ebin/hipe_amd64_pp.beam ../ebin/hipe_amd64_ra.beam ../ebin/hipe_amd64_ra_finalise.beam ../ebin/hipe_amd64_ra_ls.beam ../ebin/hipe_amd64_ra_naive.beam ../ebin/hipe_amd64_ra_postconditions.beam ../ebin/hipe_amd64_ra_sse2_postconditions.beam ../ebin/hipe_amd64_ra_x87_ls.beam ../ebin/hipe_amd64_registers.beam ../ebin/hipe_amd64_spill_restore.beam ../ebin/hipe_amd64_x87.beam ../ebin/hipe_rtl_to_amd64.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_arm.beam ../ebin/hipe_arm_assemble.beam ../ebin/hipe_arm_cfg.beam ../ebin/hipe_arm_defuse.beam ../ebin/hipe_arm_encode.beam ../ebin/hipe_arm_finalise.beam ../ebin/hipe_arm_frame.beam ../ebin/hipe_arm_liveness_gpr.beam ../ebin/hipe_arm_main.beam ../ebin/hipe_arm_pp.beam ../ebin/hipe_arm_ra.beam ../ebin/hipe_arm_ra_finalise.beam ../ebin/hipe_arm_ra_ls.beam ../ebin/hipe_arm_ra_naive.beam ../ebin/hipe_arm_ra_postconditions.beam ../ebin/hipe_arm_registers.beam ../ebin/hipe_rtl_to_arm.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_spillmin.beam ../ebin/hipe_spillmin_color.beam ../ebin/hipe_spillmin_scan.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
/usr/bin/install -c -d "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
/usr/bin/install -c -m 644 ../ebin/hipe_profile.beam ../ebin/hipe_jit.beam "/usr/local/lib/erlang/lib/hipe-3.15.2/ebin"
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
make -w RELEASE_PATH="/usr/local/lib/erlang"   release_spec
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
/usr/bin/install -c -d /usr/local/lib/erlang/lib/hipe-3.15.2/llvm
/usr/bin/install -c -m 644 elf_format.erl hipe_llvm.erl hipe_llvm_liveness.erl hipe_llvm_main.erl hipe_llvm_merge.erl hipe_rtl_to_llvm.erl elf_format.hrl elf32_format.hrl elf64_format.hrl hipe_llvm_arch.hrl /usr/local/lib/erlang/lib/hipe-3.15.2/llvm
/usr/bin/install -c -d /usr/local/lib/erlang/lib/hipe-3.15.2/ebin
/usr/bin/install -c -m 644 ../ebin/elf_format.beam ../ebin/hipe_llvm.beam ../ebin/hipe_llvm_liveness.beam ../ebin/hipe_llvm_main.beam ../ebin/hipe_llvm_merge.beam ../ebin/hipe_rtl_to_llvm.beam /usr/local/lib/erlang/lib/hipe-3.15.2/ebin
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
test -d "/usr/local/lib/erlang/releases/19" || mkdir -p "/usr/local/lib/erlang/releases/19" ;			\
	if test ! -f "/usr/local/lib/erlang/releases/19/installed_application_versions" ; then				\
	 echo "hipe-3.15.2" > "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	else								\
	 if test x = x`grep hipe-3.15.2 "/usr/local/lib/erlang/releases/19/installed_application_versions"` ; then \
	  echo hipe-3.15.2 >> "/usr/local/lib/erlang/releases/19/installed_application_versions" || exit 1;	\
	 fi ;								\
	fi
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
=== Leaving application hipe
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
(cd "/usr/local/lib/erlang" \
	 && ./Install  -minimal "/usr/local/lib/erlang")

/usr/bin/install -c -m 644 "/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/OTP_VERSION" "/usr/local/lib/erlang/releases/19"
cd /usr/local/bin
rm -f erl
rm -f erlc
rm -f epmd
rm -f run_erl
rm -f to_erl
rm -f dialyzer
rm -f typer
rm -f escript
rm -f ct_run
ln -s ../lib/erlang/bin/erl erl
ln -s ../lib/erlang/bin/erlc erlc
ln -s ../lib/erlang/bin/epmd epmd
ln -s ../lib/erlang/bin/run_erl run_erl
ln -s ../lib/erlang/bin/to_erl to_erl
ln -s ../lib/erlang/bin/dialyzer dialyzer
ln -s ../lib/erlang/bin/typer typer
ln -s ../lib/erlang/bin/escript escript
ln -s ../lib/erlang/bin/ct_run ct_run
```

**Verifying**

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ which erl
/usr/local/bin/erl
```
