**Building**

```sh
droid@droidserver:~/software/Erlang/OTP-19.1/otp_src_19.1$ make
 MAKE	depend
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	generate
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_x86_asm.h
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_amd64_asm.h
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_sparc_asm.h
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_ppc_asm.h
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_arm_asm.h
 GEN	x86_64-unknown-linux-gnu/opt/plain/erl_alloc_types.h
 GEN	x86_64-unknown-linux-gnu/opt/plain/OPCODES-GENERATED
 GEN	x86_64-unknown-linux-gnu/TABLES-GENERATED
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_mkliterals.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/hipe_mkliterals
 GEN	x86_64-unknown-linux-gnu/opt/plain/hipe_literals.h
 GEN	x86_64-unknown-linux-gnu/erl_version.h
 GEN	x86_64-unknown-linux-gnu/opt/plain/driver_tab.c
 GEN	x86_64-unknown-linux-gnu/opt/plain/GENERATED
 GEN	x86_64-unknown-linux-gnu/preload.c
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	depend
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/opt/plain/depend.mk
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	depend
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 GEN	obj/x86_64-unknown-linux-gnu/opt/depend.mk
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[4]: Nothing to be done for `depend'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[2]: Nothing to be done for `depend'.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	depend
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[2]: Nothing to be done for `depend'.
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	emulator
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_x86_asm.h
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_amd64_asm.h
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_sparc_asm.h
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_ppc_asm.h
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_arm_asm.h
 GEN	x86_64-unknown-linux-gnu/opt/smp/erl_alloc_types.h
 GEN	x86_64-unknown-linux-gnu/opt/smp/OPCODES-GENERATED
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_mkliterals.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/hipe_mkliterals.smp
 GEN	x86_64-unknown-linux-gnu/opt/smp/hipe_literals.h
 GEN	x86_64-unknown-linux-gnu/opt/smp/driver_tab.c
 GEN	x86_64-unknown-linux-gnu/opt/smp/GENERATED
 GEN	x86_64-unknown-linux-gnu/opt/smp/depend.mk
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	depend
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[5]: Nothing to be done for `depend'.
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_main.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/preload.o
 EMU_CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_emu.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_opcodes.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_load.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_bif_load.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_bp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_catches.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/code_ix.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/beam_ranges.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_pbifs.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_mtrace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_alloc_util.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_goodfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bestfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_afit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_instrument.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_init.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_atom_table.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_table.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_ddll.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_guard.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_info.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_op.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_os.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_lists.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_trace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_unique.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_wrap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_trace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/copy.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/utils.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/bif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/io.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_printf_term.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_md5.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_message.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_process.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_process_dict.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_process_lock.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_port_task.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_arith.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/time.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_time_sup.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/external.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/dist.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/binary.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_db.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_db_util.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_db_hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_db_tree.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_thr_progress.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/big.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/index.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/atom.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/module.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/export.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/register.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/break.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_async.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_lock_check.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_gc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_lock_count.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_posix_str.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bits.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_math.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_fun.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_port.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_term.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_node_tables.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_monitors.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_process_dump.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_hl_timer.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_cpu_topology.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_drv_thread.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_chksum.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_re.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_unicode.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/packet_parser.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/safe_hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_zlib.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_nif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_bif_binary.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_ao_firstfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_thr_queue.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_sched_spec_pre_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_ptab.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_map.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_msacc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/sys.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/sys_drivers.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/sys_uds.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/driver_tab.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/unix_efile.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/gzio.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/elib_memmove.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/sys_float.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/sys_time.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_poll.kp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_check_io.kp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_poll.nkp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_check_io.nkp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_mseg.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_mmap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_unix_sys_ddll.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_mtrace_sys_wrap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_sys_common_misc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_os_monotonic_time_extender.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_bif0.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_bif1.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_bif2.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_gc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_mode_switch.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_native_bif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_stack.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_amd64.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_amd64_glue.o
 M4	x86_64-unknown-linux-gnu/opt/smp/hipe_amd64_bifs.S
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_amd64_bifs.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_x86_signal.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_x86_stack.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/hipe_bif64.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erlang_lttng.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/efile_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/inet_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/zlib_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/ram_file_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/ttsl_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_tracer_nif.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_latin_1_table.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_compile.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_config.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_dfa_exec.o
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/pcre_exec_loop_break_cases.inc
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_exec.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_fullinfo.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_get.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_globals.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_maketables.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_newline.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_ord2utf8.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_refcount.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_study.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_tables.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_valid_utf8.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_version.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_byte_order.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_jit_compile.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_string_utils.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_ucd.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/pcre_xclass.o
 AR	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator/pcre/obj/x86_64-unknown-linux-gnu/opt/libepcre.a
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 MAKE	opt
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethr_aux.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethr_atomics.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethr_mutex.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethr_cbf.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethread.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/ethr_event.o
 AR	../lib/internal/x86_64-unknown-linux-gnu/libethread.a
 RANLIB	../lib/internal/x86_64-unknown-linux-gnu/libethread.a
 CC	obj/x86_64-unknown-linux-gnu/opt/erl_memory_trace_parser.o
 AR	../lib/x86_64-unknown-linux-gnu/liberts.a
 RANLIB	../lib/x86_64-unknown-linux-gnu/liberts.a
 CC	obj/x86_64-unknown-linux-gnu/opt/r/erl_memory_trace_parser.o
 AR	../lib/x86_64-unknown-linux-gnu/liberts_r.a
 RANLIB	../lib/x86_64-unknown-linux-gnu/liberts_r.a
 CC	obj/x86_64-unknown-linux-gnu/opt/erl_printf_format.o
 CC	obj/x86_64-unknown-linux-gnu/opt/erl_printf.o
 CC	obj/x86_64-unknown-linux-gnu/opt/erl_misc_utils.o
 AR	../lib/internal/x86_64-unknown-linux-gnu/liberts_internal.a
 RANLIB	../lib/internal/x86_64-unknown-linux-gnu/liberts_internal.a
 CC	obj/x86_64-unknown-linux-gnu/opt/r/erl_printf_format.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/erl_printf.o
 CC	obj/x86_64-unknown-linux-gnu/opt/r/erl_misc_utils.o
 AR	../lib/internal/x86_64-unknown-linux-gnu/liberts_internal_r.a
 RANLIB	../lib/internal/x86_64-unknown-linux-gnu/liberts_internal_r.a
 GEN	obj/x86_64-unknown-linux-gnu/opt/MADE
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/lib_src'
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/beam.smp
 CC	obj/x86_64-unknown-linux-gnu/opt/smp/erl_child_setup.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erl_child_setup
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 MAKE	opt
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
 GEN	x86_64-unknown-linux-gnu/gen_git_version.mk
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_main.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/preload.o
 EMU_CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_emu.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_opcodes.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_load.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_bif_load.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_bp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_catches.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/code_ix.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/beam_ranges.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_pbifs.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_mtrace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_alloc_util.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_goodfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bestfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_afit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_instrument.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_init.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_atom_table.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_table.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_ddll.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_guard.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_info.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_op.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_os.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_lists.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_trace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_unique.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_wrap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_trace.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/copy.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/utils.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/bif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/io.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_printf_term.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_md5.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_message.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_process.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_process_dict.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_process_lock.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_port_task.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_arith.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/time.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_time_sup.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/external.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/dist.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/binary.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_db.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_db_util.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_db_hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_db_tree.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_thr_progress.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/big.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/index.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/atom.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/module.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/export.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/register.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/break.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_async.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_lock_check.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_gc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_lock_count.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_posix_str.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bits.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_math.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_fun.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_port.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_term.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_node_tables.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_monitors.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_process_dump.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_hl_timer.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_cpu_topology.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_drv_thread.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_chksum.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_re.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_unicode.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/packet_parser.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/safe_hash.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_zlib.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_nif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_bif_binary.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_ao_firstfit_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_thr_queue.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_sched_spec_pre_alloc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_ptab.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_map.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_msacc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/sys.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/sys_drivers.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/sys_uds.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/driver_tab.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/unix_efile.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/gzio.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/elib_memmove.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/sys_float.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/sys_time.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_poll.kp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_check_io.kp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_poll.nkp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_check_io.nkp.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_mseg.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_mmap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_unix_sys_ddll.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_mtrace_sys_wrap.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_sys_common_misc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_os_monotonic_time_extender.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_bif0.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_bif1.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_bif2.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_debug.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_gc.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_mode_switch.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_native_bif.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_stack.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_amd64.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_amd64_glue.o
 M4	x86_64-unknown-linux-gnu/opt/plain/hipe_amd64_bifs.S
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_amd64_bifs.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_x86_signal.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_x86_stack.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/hipe_bif64.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erlang_lttng.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/efile_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/inet_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/zlib_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/ram_file_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/ttsl_drv.o
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_tracer_nif.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/beam
 CC	obj/x86_64-unknown-linux-gnu/opt/plain/erl_child_setup.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erl_child_setup
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/emulator'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/inet_gethost.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/inet_gethost
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/heart.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/heart
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/erlexec.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erlexec
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/typer.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/typer
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/dialyzer.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/dialyzer
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/erlc.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/erlc
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/escript.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/escript
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/ct_run.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/ct_run
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/safe_string.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/run_erl.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/run_erl
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/to_erl.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/to_erl
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/dyn_erl.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/dyn_erl
 VSN	Install
 VSN	erl.src
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/common'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
 GEN	etp-commands
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc/unix'
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/etc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/epmd/src'
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/epmd.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/epmd_cli.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/obj/x86_64-unknown-linux-gnu/epmd_srv.o
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/x86_64-unknown-linux-gnu/epmd
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
 VSN	../ebin/erts.app
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/preloaded/src'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
 MAKE	secondary_bootstrap_build
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe'
Makefile:72: warning: overriding commands for target `clean'
/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/make/otp_subdir.mk:29: warning: ignoring old commands for target `clean'
=== Entering application hipe
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
 VSN	hipe.hrl
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
 ERLC	../ebin/hipe_rtl.beam
 ERLC	../ebin/hipe_rtl_cfg.beam
 ERLC	../ebin/hipe_rtl_liveness.beam
 GEN	hipe_literals.hrl
 ERLC	../ebin/hipe_icode2rtl.beam
 ERLC	../ebin/hipe_rtl_mk_switch.beam
 ERLC	../ebin/hipe_rtl_primops.beam
 ERLC	../ebin/hipe_rtl_varmap.beam
 ERLC	../ebin/hipe_rtl_exceptions.beam
 ERLC	../ebin/hipe_rtl_binary_match.beam
 ERLC	../ebin/hipe_rtl_binary_construct.beam
 ERLC	../ebin/hipe_rtl_arith_32.beam
 ERLC	../ebin/hipe_rtl_arith_64.beam
 ERLC	../ebin/hipe_rtl_ssa.beam
 ERLC	../ebin/hipe_rtl_ssa_const_prop.beam
 ERLC	../ebin/hipe_rtl_cleanup_const.beam
 ERLC	../ebin/hipe_rtl_symbolic.beam
 ERLC	../ebin/hipe_rtl_lcm.beam
 ERLC	../ebin/hipe_rtl_ssapre.beam
 ERLC	../ebin/hipe_rtl_binary.beam
 ERLC	../ebin/hipe_rtl_ssa_avail_expr.beam
 ERLC	../ebin/hipe_rtl_arch.beam
 ERLC	../ebin/hipe_tagscheme.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/rtl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
 ERLC	../ebin/hipe_consttab.beam
 ERLC	../ebin/hipe_gensym.beam
 ERLC	../ebin/hipe_data_pp.beam
 ERLC	../ebin/hipe_pack_constants.beam
 ERLC	../ebin/hipe_sdi.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/misc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
 ERLC	../ebin/hipe_main.beam
 ERLC	../ebin/hipe.beam
 VSN	../ebin/hipe.app
 VSN	../ebin/hipe.appup
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/main'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
 ERLC	../ebin/cerl_cconv.beam
 ERLC	../ebin/cerl_closurean.beam
 ERLC	../ebin/cerl_hipeify.beam
 ERLC	../ebin/cerl_lib.beam
 ERLC	../ebin/cerl_messagean.beam
 ERLC	../ebin/cerl_pmatch.beam
 ERLC	../ebin/cerl_prettypr.beam
 ERLC	../ebin/cerl_to_icode.beam
 ERLC	../ebin/cerl_typean.beam
 ERLC	../ebin/erl_bif_types.beam
 ERLC	../ebin/erl_types.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/cerl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
 ERLC	../ebin/hipe_beam_to_icode.beam
 ERLC	../ebin/hipe_icode.beam
 ERLC	../ebin/hipe_icode_bincomp.beam
 ERLC	../ebin/hipe_icode_callgraph.beam
 ERLC	../ebin/hipe_icode_cfg.beam
 ERLC	../ebin/hipe_icode_coordinator.beam
 ERLC	../ebin/hipe_icode_fp.beam
 ERLC	../ebin/hipe_icode_exceptions.beam
 ERLC	../ebin/hipe_icode_inline_bifs.beam
 ERLC	../ebin/hipe_icode_instruction_counter.beam
 ERLC	../ebin/hipe_icode_liveness.beam
 ERLC	../ebin/hipe_icode_pp.beam
 ERLC	../ebin/hipe_icode_primops.beam
 ERLC	../ebin/hipe_icode_range.beam
 ERLC	../ebin/hipe_icode_split_arith.beam
 ERLC	../ebin/hipe_icode_ssa.beam
 ERLC	../ebin/hipe_icode_ssa_const_prop.beam
 ERLC	../ebin/hipe_icode_call_elim.beam
 ERLC	../ebin/hipe_icode_ssa_copy_prop.beam
 ERLC	../ebin/hipe_icode_ssa_struct_reuse.beam
 ERLC	../ebin/hipe_icode_type.beam
 ERLC	../ebin/hipe_icode_heap_test.beam
 ERLC	../ebin/hipe_icode_ebb.beam
 ERLC	../ebin/hipe_icode_mulret.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/icode'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
 ERLC	../ebin/hipe_bb.beam
 ERLC	../ebin/hipe_dominators.beam
 ERLC	../ebin/hipe_gen_cfg.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/flow'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
 ERLC	../ebin/hipe_timing.beam
 ERLC	../ebin/hipe_dot.beam
 ERLC	../ebin/hipe_digraph.beam
 ERLC	../ebin/hipe_vectors.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/util'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
 ERLC	../ebin/hipe_ig.beam
 ERLC	../ebin/hipe_ig_moves.beam
 ERLC	../ebin/hipe_moves.beam
 ERLC	../ebin/hipe_node_sets.beam
 ERLC	../ebin/hipe_spillcost.beam
 ERLC	../ebin/hipe_reg_worklists.beam
 ERLC	../ebin/hipe_adj_list.beam
 ERLC	../ebin/hipe_temp_map.beam
 ERLC	../ebin/hipe_optimistic_regalloc.beam
 ERLC	../ebin/hipe_coalescing_regalloc.beam
 ERLC	../ebin/hipe_graph_coloring_regalloc.beam
 ERLC	../ebin/hipe_regalloc_loop.beam
 ERLC	../ebin/hipe_ls_regalloc.beam
 ERLC	../ebin/hipe_ppc_specific.beam
 ERLC	../ebin/hipe_ppc_specific_fp.beam
 ERLC	../ebin/hipe_sparc_specific.beam
 ERLC	../ebin/hipe_sparc_specific_fp.beam
 ERLC	../ebin/hipe_arm_specific.beam
 ERLC	../ebin/hipe_x86_specific.beam
 ERLC	../ebin/hipe_x86_specific_x87.beam
 ERLC	../ebin/hipe_amd64_specific.beam
 ERLC	../ebin/hipe_amd64_specific_sse2.beam
 ERLC	../ebin/hipe_amd64_specific_x87.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/regalloc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
 ERLC	../ebin/hipe_rtl_to_sparc.beam
 ERLC	../ebin/hipe_sparc.beam
 ERLC	../ebin/hipe_sparc_assemble.beam
 ERLC	../ebin/hipe_sparc_cfg.beam
 ERLC	../ebin/hipe_sparc_defuse.beam
 ERLC	../ebin/hipe_sparc_encode.beam
 ERLC	../ebin/hipe_sparc_finalise.beam
 ERLC	../ebin/hipe_sparc_frame.beam
 ERLC	../ebin/hipe_sparc_liveness_all.beam
 ERLC	../ebin/hipe_sparc_liveness_fpr.beam
 ERLC	../ebin/hipe_sparc_liveness_gpr.beam
 ERLC	../ebin/hipe_sparc_main.beam
 ERLC	../ebin/hipe_sparc_pp.beam
 ERLC	../ebin/hipe_sparc_ra.beam
 ERLC	../ebin/hipe_sparc_ra_finalise.beam
 ERLC	../ebin/hipe_sparc_ra_ls.beam
 ERLC	../ebin/hipe_sparc_ra_naive.beam
 ERLC	../ebin/hipe_sparc_ra_postconditions.beam
 ERLC	../ebin/hipe_sparc_ra_postconditions_fp.beam
 ERLC	../ebin/hipe_sparc_registers.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/sparc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
 ERLC	../ebin/hipe_ppc.beam
 ERLC	../ebin/hipe_ppc_assemble.beam
 ERLC	../ebin/hipe_ppc_cfg.beam
 ERLC	../ebin/hipe_ppc_defuse.beam
 ERLC	../ebin/hipe_ppc_encode.beam
 ERLC	../ebin/hipe_ppc_finalise.beam
 ERLC	../ebin/hipe_ppc_frame.beam
 ERLC	../ebin/hipe_ppc_liveness_all.beam
 ERLC	../ebin/hipe_ppc_liveness_fpr.beam
 ERLC	../ebin/hipe_ppc_liveness_gpr.beam
 ERLC	../ebin/hipe_ppc_main.beam
 ERLC	../ebin/hipe_ppc_pp.beam
 ERLC	../ebin/hipe_ppc_ra.beam
 ERLC	../ebin/hipe_ppc_ra_finalise.beam
 ERLC	../ebin/hipe_ppc_ra_ls.beam
 ERLC	../ebin/hipe_ppc_ra_naive.beam
 ERLC	../ebin/hipe_ppc_ra_postconditions.beam
 ERLC	../ebin/hipe_ppc_ra_postconditions_fp.beam
 ERLC	../ebin/hipe_ppc_registers.beam
 ERLC	../ebin/hipe_rtl_to_ppc.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/ppc'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
 ERLC	../ebin/hipe_rtl_to_x86.beam
 ERLC	../ebin/hipe_x86.beam
 ERLC	../ebin/hipe_x86_assemble.beam
 ERLC	../ebin/hipe_x86_cfg.beam
 ERLC	../ebin/hipe_x86_defuse.beam
 ERLC	../ebin/hipe_x86_encode.beam
 ERLC	../ebin/hipe_x86_frame.beam
 ERLC	../ebin/hipe_x86_liveness.beam
 ERLC	../ebin/hipe_x86_main.beam
 ERLC	../ebin/hipe_x86_postpass.beam
 ERLC	../ebin/hipe_x86_pp.beam
 ERLC	../ebin/hipe_x86_ra.beam
 ERLC	../ebin/hipe_x86_ra_finalise.beam
 ERLC	../ebin/hipe_x86_ra_ls.beam
 ERLC	../ebin/hipe_x86_ra_naive.beam
 ERLC	../ebin/hipe_x86_ra_postconditions.beam
 ERLC	../ebin/hipe_x86_ra_x87_ls.beam
 ERLC	../ebin/hipe_x86_registers.beam
 ERLC	../ebin/hipe_x86_spill_restore.beam
 ERLC	../ebin/hipe_x86_x87.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/x86'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
 ERLC	../ebin/hipe_amd64_assemble.beam
 ERLC	../ebin/hipe_amd64_defuse.beam
 ERLC	../ebin/hipe_amd64_encode.beam
 ERLC	../ebin/hipe_amd64_frame.beam
 ERLC	../ebin/hipe_amd64_liveness.beam
 ERLC	../ebin/hipe_amd64_main.beam
 ERLC	../ebin/hipe_amd64_pp.beam
 ERLC	../ebin/hipe_amd64_ra.beam
 ERLC	../ebin/hipe_amd64_ra_finalise.beam
 ERLC	../ebin/hipe_amd64_ra_ls.beam
 ERLC	../ebin/hipe_amd64_ra_naive.beam
 ERLC	../ebin/hipe_amd64_ra_postconditions.beam
 ERLC	../ebin/hipe_amd64_ra_sse2_postconditions.beam
 ERLC	../ebin/hipe_amd64_ra_x87_ls.beam
 ERLC	../ebin/hipe_amd64_registers.beam
 ERLC	../ebin/hipe_amd64_spill_restore.beam
 ERLC	../ebin/hipe_amd64_x87.beam
 ERLC	../ebin/hipe_rtl_to_amd64.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/amd64'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
 ERLC	../ebin/hipe_arm.beam
 ERLC	../ebin/hipe_arm_assemble.beam
 ERLC	../ebin/hipe_arm_cfg.beam
 ERLC	../ebin/hipe_arm_defuse.beam
 ERLC	../ebin/hipe_arm_encode.beam
 ERLC	../ebin/hipe_arm_finalise.beam
 ERLC	../ebin/hipe_arm_frame.beam
 ERLC	../ebin/hipe_arm_liveness_gpr.beam
 ERLC	../ebin/hipe_arm_main.beam
 ERLC	../ebin/hipe_arm_pp.beam
 ERLC	../ebin/hipe_arm_ra.beam
 ERLC	../ebin/hipe_arm_ra_finalise.beam
 ERLC	../ebin/hipe_arm_ra_ls.beam
 ERLC	../ebin/hipe_arm_ra_naive.beam
 ERLC	../ebin/hipe_arm_ra_postconditions.beam
 ERLC	../ebin/hipe_arm_registers.beam
 ERLC	../ebin/hipe_rtl_to_arm.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/arm'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
 ERLC	../ebin/hipe_spillmin.beam
 ERLC	../ebin/hipe_spillmin_color.beam
 ERLC	../ebin/hipe_spillmin_scan.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/opt'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
 ERLC	../ebin/hipe_profile.beam
 ERLC	../ebin/hipe_jit.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/tools'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/hipe/llvm'
 ERLC	../ebin/elf_format.beam
 ERLC	../ebin/hipe_llvm.beam
 ERLC	../ebin/hipe_llvm_liveness.beam
 ERLC	../ebin/hipe_llvm_main.beam
 ERLC	../ebin/hipe_llvm_merge.beam
 ERLC	../ebin/hipe_rtl_to_llvm.beam
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
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpAuthException.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangDecodeException.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangExit.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangBoolean.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangByte.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangChar.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangFloat.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangShort.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangUInt.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpErlangUShort.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/Link.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/Links.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpCookedConnection.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpServer.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/priv/com/ericsson/otp/erlang/OtpSystem.class
 VSN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/ebin/jinterface.app
 VSN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/jinterface/ebin/jinterface.appup
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
 CC	../priv/obj/x86_64-unknown-linux-gnu/ic.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/ic_tmo.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_version.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_long.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_ulong.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_double.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_char.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_string.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_atom.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_pid.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_port.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_ref.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_term.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_tuple_header.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_list_header.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_longlong.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_ulonglong.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_wchar.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_encode_wstring.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_decode_longlong.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_decode_ulonglong.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_decode_wchar.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_decode_wstring.o
 CC	../priv/obj/x86_64-unknown-linux-gnu/oe_ei_code_erlang_binary.o
 AR	../priv/lib/x86_64-unknown-linux-gnu/libic.a
 RANLIB	../priv/lib/x86_64-unknown-linux-gnu/libic.a
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic'
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Holder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/BooleanHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/ByteHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/CharHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/DoubleHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/FloatHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/IntHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/LongHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/ShortHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/StringHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Environment.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Any.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/AnyHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Pid.class
Note: Pid.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/PidHolder.class
Note: /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic/Pid.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Ref.class
Note: Ref.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/RefHolder.class
Note: /home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/java_src/com/ericsson/otp/ic/Ref.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Port.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/PortHolder.class
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/Term.class
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
 JAVAC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ic/priv/com/ericsson/otp/ic/TermHolder.class
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
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
 MAKE	libs
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
=== Entering application stdlib
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib/examples'
=== Leaving application stdlib
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/stdlib'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
=== Entering application kernel
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
 ERLC	../ebin/hipe_unified_loader.beam
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel/examples'
=== Leaving application kernel
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/kernel'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
=== Entering application compiler
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler/doc/src'
=== Leaving application compiler
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/compiler'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
=== Entering application tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
 CC	../obj/x86_64-unknown-linux-gnu/opt/emem/erl_memory.o
 CC	../obj/x86_64-unknown-linux-gnu/opt/emem/erl_memory_trace_block_table.o
 LD	../bin/x86_64-unknown-linux-gnu/emem
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools/emacs'
=== Leaving application tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
=== Entering application common_test
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[4]: Nothing to be done for `debug'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test/priv'
=== Leaving application common_test
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/common_test'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
=== Entering application runtime_tools
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
 CC	../priv/obj/x86_64-unknown-linux-gnu/dyntrace.o
 LD	../priv/lib/x86_64-unknown-linux-gnu/dyntrace.so
 CC	../priv/obj/x86_64-unknown-linux-gnu/trace_file_drv.o
 LD	../priv/lib/x86_64-unknown-linux-gnu/trace_file_drv.so
 CC	../priv/obj/x86_64-unknown-linux-gnu/trace_ip_drv.o
 LD	../priv/lib/x86_64-unknown-linux-gnu/trace_ip_drv.so
rm ../priv/obj/x86_64-unknown-linux-gnu/trace_file_drv.o ../priv/obj/x86_64-unknown-linux-gnu/trace_ip_drv.o ../priv/obj/x86_64-unknown-linux-gnu/dyntrace.o
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools/doc/src'
=== Leaving application runtime_tools
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/runtime_tools'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
=== Entering application inets
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/inets_app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_lib'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_client'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/http_server'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/ftp'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src/tftp'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/server_root'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples/httpd_load_test'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets/doc/src'
=== Leaving application inets
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/inets'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
=== Entering application xmerl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl/doc/src'
=== Leaving application xmerl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/xmerl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
=== Entering application edoc
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/include'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc/doc/src'
=== Leaving application edoc
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/edoc'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
=== Entering application erl_docgen
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/bin'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/css'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_html_entities'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/dtd_man_entities'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/images'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/js/flipmenu'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv/xsl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen/doc/src'
=== Leaving application erl_docgen
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_docgen'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
=== Entering application otp_mibs
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs/doc/src'
=== Leaving application otp_mibs
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/otp_mibs'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
=== Entering application erl_interface
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_connect.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_resolve.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/eirecv.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/send.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/send_exit.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/send_reg.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_atom.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_big.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_bignum.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_binary.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_boolean.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_char.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_double.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_fun.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_intlist.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_list_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_long.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_pid.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_ref.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_skip.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_string.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_tuple_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_ulong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_version.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_longlong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_ulonglong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_atom.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_big.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_bignum.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_binary.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_boolean.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_char.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_double.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_fun.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_list_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_long.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_pid.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_ref.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_string.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_tuple_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_ulong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_version.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_longlong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_ulonglong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/epmd_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/epmd_publish.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/epmd_unpublish.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_decode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_format.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_locking.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_malloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_portio.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_printterm.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_pthreads.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_x_encode.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/eimd5.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/get_type.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/show_msg.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/ei_compat.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_dohash.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_foreach.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_freetab.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_insert.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_isprime.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_lookup.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_newtab.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_remove.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_resize.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/hash_rlookup.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_close.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_delete.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_dirty.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_dump.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_free.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_get.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_getf.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_geti.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_getp.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_gets.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_make.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_open.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_purge.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_resize.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_restore.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_set.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_setf.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_seti.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_setp.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_sets.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_stat.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/reg_tabstat.o
 AR	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei_st.a
 RANLIB	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei_st.a
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/decode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/encode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_connect.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_error.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_eterm.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_fix_alloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_format.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_malloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_marshal.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_resolve.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/erl_timeout.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/global_names.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/global_register.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/global_unregister.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.st/x86_64-unknown-linux-gnu/global_whereis.o
 AR	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface_st.a
 RANLIB	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface_st.a
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_connect.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_resolve.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/eirecv.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/send.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/send_exit.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/send_reg.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_atom.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_big.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_bignum.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_binary.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_boolean.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_char.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_double.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_fun.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_intlist.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_list_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_long.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_pid.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_ref.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_skip.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_string.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_tuple_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_ulong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_version.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_longlong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_ulonglong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_atom.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_big.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_bignum.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_binary.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_boolean.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_char.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_double.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_fun.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_list_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_long.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_pid.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_ref.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_string.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_tuple_header.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_ulong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_version.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_longlong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_ulonglong.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/epmd_port.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/epmd_publish.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/epmd_unpublish.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_decode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_format.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_locking.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_malloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_portio.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_printterm.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_pthreads.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_trace.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_x_encode.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/eimd5.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/get_type.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/show_msg.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/ei_compat.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_dohash.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_foreach.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_freetab.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_insert.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_isprime.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_lookup.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_newtab.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_remove.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_resize.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/hash_rlookup.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_close.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_delete.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_dirty.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_dump.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_free.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_get.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_getf.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_geti.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_getp.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_gets.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_make.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_open.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_purge.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_resize.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_restore.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_set.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_setf.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_seti.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_setp.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_sets.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_stat.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/reg_tabstat.o
 AR	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei.a
 RANLIB	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/libei.a
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/decode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/encode_term.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_connect.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_error.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_eterm.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_fix_alloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_format.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_malloc.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_marshal.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_resolve.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/erl_timeout.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/global_names.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/global_register.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/global_unregister.o
 CC	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj.mt/x86_64-unknown-linux-gnu/global_whereis.o
 AR	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface.a
 RANLIB	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/obj/x86_64-unknown-linux-gnu/liberl_interface.a
 LD	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/bin/x86_64-unknown-linux-gnu/erl_call
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface/doc/src'
=== Leaving application erl_interface
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/erl_interface'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
=== Entering application asn1
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
 CC	../priv/obj/x86_64-unknown-linux-gnu/asn1_erl_nif.o
 LD	../priv/lib/x86_64-unknown-linux-gnu/asn1rt_nif.so
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1/c_src'
=== Leaving application asn1
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/asn1'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
=== Entering application wx
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/demo'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/sudoku'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/simple'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples/xrc'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx/doc/src'
=== Leaving application wx
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/wx'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
=== Entering application debugger
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger/doc/src'
=== Leaving application debugger
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/debugger'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
=== Entering application reltool
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool/doc/src'
=== Leaving application reltool
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/reltool'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
=== Entering application gs
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[4]: Nothing to be done for `debug'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/tcl'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs/doc/src'
=== Leaving application gs
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/gs'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
=== Entering application mnesia
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/include'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia/doc/src'
=== Leaving application mnesia
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/mnesia'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
=== Entering application crypto
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
 CC	../priv/obj/x86_64-unknown-linux-gnu/crypto.o
 LD	../priv/lib/x86_64-unknown-linux-gnu/crypto.so
 CC	../priv/obj/x86_64-unknown-linux-gnu/crypto_callback.o
/usr/bin/install -c -d ../priv/lib/x86_64-unknown-linux-gnu
gcc -shared -Wl,-Bsymbolic -o ../priv/lib/x86_64-unknown-linux-gnu/crypto_callback.so ../priv/obj/x86_64-unknown-linux-gnu/crypto_callback.o
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto/doc/src'
=== Leaving application crypto
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/crypto'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
=== Entering application orber
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/COSS/CosNaming'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src/Orber'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/java_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
mkdir -p ../priv/obj/x86_64-unknown-linux-gnu
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples/Stack'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber/priv'
=== Leaving application orber
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/orber'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
=== Entering application os_mon
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
 MAKE	opt
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
 CC	../priv/obj/x86_64-unknown-linux-gnu/memsup.o
 LD	../priv/bin/x86_64-unknown-linux-gnu/memsup
 CC	../priv/obj/x86_64-unknown-linux-gnu/cpu_sup.o
 LD	../priv/bin/x86_64-unknown-linux-gnu/cpu_sup
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/c_src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/mibs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon/doc/src'
=== Leaving application os_mon
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/os_mon'
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
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
=== Entering application public_key
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/asn1'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key/doc/src'
=== Leaving application public_key
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/public_key'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
=== Entering application ssl
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/certs'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl/examples/src'
=== Leaving application ssl
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssl'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
=== Entering application observer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer/doc/src'
=== Leaving application observer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/observer'
=== Skipping subdir odbc, reason:
ODBC library - link check failed
===
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
=== Entering application diameter
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter/doc/src'
=== Leaving application diameter
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/diameter'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
=== Entering application cosTransactions
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions/doc/src'
=== Leaving application cosTransactions
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTransactions'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
=== Entering application cosEvent
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent/doc/src'
=== Leaving application cosEvent
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEvent'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
=== Entering application cosTime
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime/doc/src'
=== Leaving application cosTime
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosTime'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
=== Entering application cosNotification
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification/doc/src'
=== Leaving application cosNotification
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosNotification'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
=== Entering application cosProperty
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty/doc/src'
=== Leaving application cosProperty
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosProperty'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
=== Entering application cosFileTransfer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer/doc/src'
=== Leaving application cosFileTransfer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosFileTransfer'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
=== Entering application cosEventDomain
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain/doc/src'
=== Leaving application cosEventDomain
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/cosEventDomain'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
=== Entering application et
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et/doc/src'
=== Leaving application et
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/et'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
=== Entering application megaco
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/app'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/engine'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/text'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
 MAKE	opt
make[5]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
 ERLC	../../ebin/megaco_flex_scanner.beam
 ERLC	../../ebin/megaco_flex_scanner_handler.beam
make[5]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/flex'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
 GEN	prebuild.skip
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/binary'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/tcp'
make[4]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
make[4]: Nothing to be done for `opt'.
make[4]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src/udp'
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/simple'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/examples/meas'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco/doc/src'
=== Leaving application megaco
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/megaco'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
=== Entering application eunit
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/examples'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit/doc/src'
=== Leaving application eunit
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eunit'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
=== Entering application ssh
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh/doc/src'
=== Leaving application ssh
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/ssh'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
=== Entering application typer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer/doc/src'
=== Leaving application typer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/typer'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
=== Entering application percept
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/priv'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept/doc/src'
=== Leaving application percept
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/percept'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
=== Entering application eldap
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap/doc/src'
=== Leaving application eldap
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/eldap'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
=== Entering application dialyzer
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/src'
make[3]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
make[3]: Nothing to be done for `opt'.
make[3]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer/doc/src'
=== Leaving application dialyzer
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib/dialyzer'
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
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/lib'
make[1]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/start_clean.rel
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/start_sasl.rel
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/start_all_example.rel
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/no_dot_erlang.rel
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/start_clean.script
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/start_sasl.boot
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts/no_dot_erlang.boot
 GEN	RELEASES.src
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make[2]: Entering directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/start.script
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/start_sasl.script
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/start_clean.script
 GEN	/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/bin/no_dot_erlang.script
make[2]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts/start_scripts'
make[1]: Leaving directory `/home/droid/software/Erlang/OTP-19.1/otp_src_19.1/erts'
```
