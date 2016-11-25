**Testing**

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ make release_tests
if test -f lib/common_test/test_server/Makefile; then \
	    (cd lib/common_test/test_server; make TESTROOT="/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/release/tests" \
	    PATH=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/:/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bootstrap/bin:"${PATH}" release_tests) || exit $?; \
	fi
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/test_server'
Makefile:21: /make/target.mk: No such file or directory
Makefile:26: /make/x86_64-unknown-linux-gnu/otp.mk: No such file or directory
Makefile:85: /make/otp_release_targets.mk: No such file or directory
make[1]: *** No rule to make target `/make/otp_release_targets.mk'.  Stop.
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/test_server'
make: *** [lib/common_test/test_server] Error 2
```

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ sudo make release_tests
[sudo] password for droid:
if test -f lib/common_test/test_server/Makefile; then \
	    (cd lib/common_test/test_server; make TESTROOT="/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/release/tests" \
	    PATH=/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/:/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bootstrap/bin:"${PATH}" release_tests) || exit $?; \
	fi
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/test_server'
Makefile:21: /make/target.mk: No such file or directory
Makefile:26: /make/x86_64-unknown-linux-gnu/otp.mk: No such file or directory
Makefile:85: /make/otp_release_targets.mk: No such file or directory
make[1]: *** No rule to make target `/make/otp_release_targets.mk'.  Stop.
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/test_server'
make: *** [lib/common_test/test_server] Error 2
```
