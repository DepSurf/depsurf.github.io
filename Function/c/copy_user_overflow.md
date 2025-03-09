# Function: <code>copy_user_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void copy_user_overflow(int size, long unsigned int count)
```

```json
{
  "name": "copy_user_overflow",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579414849,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_put_long"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/sysctl_binary.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579423958,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:SyS_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429628,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_readdata"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579460845,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:SyS_setdomainname",
        "kernel/sys.c:SyS_sethostname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568054,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/power/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/time/timer_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/trace/trace_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/statfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581448933,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/dcookies.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582160080,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582253801,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/ecryptfs/miscdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "fs/efivarfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/msgutil.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "ipc/compat_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/user_defined.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "security/integrity/evm/evm_secfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "block/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "block/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "block/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "lib/seq_buf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/pinctrl/pinconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/xen/mcelog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/vt/vc_screen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584513934,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/agp/frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/agp/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/base/regmap/regmap-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585461976,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/input/input-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585974042,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586604695,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586620502,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586689434,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/core/dev_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586891308,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_SyS_socketcall"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587020873,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587053647,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587725754,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/wireless/wext-priv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:707",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160080,
      "name": "copy_user_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void copy_user_overflow(int size, long unsigned int count)
```

```json
{
  "name": "copy_user_overflow",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/tls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/cpu/mtrr/if.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/crash_dump_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/kernel/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579435153,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_put_long"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/sysctl_binary.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579444246,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:SyS_capget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450003,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_readdata"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579481261,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:SyS_setdomainname",
        "kernel/sys.c:SyS_sethostname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593030,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_getattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/power/qos.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/power/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/itimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/time/timer_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580027017,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:C_SYSC_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/trace/trace_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581020242,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/seq_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/utimes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/statfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581529855,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/crypto/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/fhandle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/quota/quota.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/proc/vmcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/dcookies.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582249488,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582343279,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/ecryptfs/miscdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "fs/efivarfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/msgutil.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "ipc/compat_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/user_defined.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/dh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/trusted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/smack/smack_lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "security/integrity/evm/evm_secfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "block/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "block/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "block/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "lib/seq_buf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "lib/kfifo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/pinctrl/pinconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/video/fbdev/core/fbcmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/acpi/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/xen/mcelog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/vt/vt_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/vt/vc_screen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584695994,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/agp/frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/agp/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/base/regmap/regmap-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/nvdimm/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/scsi/scsi_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/scsi/scsi_devinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/scsi/scsi_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/gpu/vga/vga_switcheroo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585665578,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/input/input-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586162351,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/input/misc/uinput.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586789143,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586805062,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586875384,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/core/dev_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587085388,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_SyS_socketcall"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587216697,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587249551,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587940154,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/wireless/wext-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/wireless/wext-priv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "copy_user_overflow",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:686",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249488,
      "name": "copy_user_overflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void copy_user_overflow(int size, long unsigned int count)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void copy_user_overflow(int size, long unsigned int count)
```
</details>
</li>
</ul>
