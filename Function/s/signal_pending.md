# Function: <code>signal_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858904,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/entry/common.c:syscall_trace_enter_phase2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284059,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365959,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383228,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415465,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425202,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364787,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646179,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:prepare_to_wait_event",
        "kernel/sched/wait.c:bit_wait",
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/wait.c:bit_wait_io_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369508,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371759,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374776,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375785,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791339,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813575,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378897,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579841848,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874345,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894927,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139384,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_phase2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198150,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452142,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472486,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580487787,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580514454,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522578,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580552763,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591773,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636827,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:try_to_compact_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580658550,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580713786,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767619,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580794620,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828395,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587341254,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580916781,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_resize_limit",
        "mm/memcontrol.c:mem_cgroup_resize_memsw_limit",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973918,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019569,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581027777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072310,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078753,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_sys_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_to_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226927,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277732,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283286,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292219,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299980,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:timerfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310065,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318925,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356803,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_core_sys_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396657,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817171,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944957,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009955,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059770,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582147409,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157593,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174576,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582274450,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630817,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648250,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:crypto_alloc_ablkcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664179,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760043,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037890,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583230103,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_pci22_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356684,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583956799,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583979318,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992532,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003529,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584089667,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157649,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167370,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:extract_entropy_user",
        "drivers/char/random.c:SyS_getrandom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584191623,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349070,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466907,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761388,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/dma-buf/fence.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585093341,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585242787,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:reap_as",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585618527,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585723714,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_do_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585792911,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:dm_wait_for_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586176933,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586195249,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586237489,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/core/datagram.c:__skb_recv_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242212,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586324014,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586505766,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586598954,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586970276,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2900",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858619,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284947,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374589,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579395669,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427865,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450333,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587866003,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869086,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:bit_wait_io_timeout",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/wait.c:bit_wait",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661811,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587870004,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875944,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876848,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879689,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816479,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579843927,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881793,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870803,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903801,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579925967,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580171579,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580233586,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529045,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549253,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600287,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606906,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580648459,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580691941,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754414,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767204,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828799,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932717,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955867,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839584,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581084301,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128958,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147295,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178847,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581187153,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581234209,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237290,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244971,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358589,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_to_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394244,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443409,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448257,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466126,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469967,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:timerfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474654,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476492,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485501,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537825,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_filldir64",
        "fs/compat.c:compat_filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574785,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721429,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805100,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012935,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156558,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273871,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582365395,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373745,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390751,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582493746,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880454,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038083,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583330482,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538807,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669836,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584299952,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584311687,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324596,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335790,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584494929,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584514586,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:SyS_getrandom",
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530838,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535552,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584803490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117963,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/dma-buf/fence.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585401149,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585459079,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585485849,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585649208,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013939,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134285,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194889,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592053,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586617721,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586661505,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586667534,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586757165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948561,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587042730,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587051169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587237633,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587416498,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3177",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300369,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579416006,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447241,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470813,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588080564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588083486,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:bit_wait_io_timeout",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/wait.c:bit_wait_io",
        "kernel/sched/wait.c:bit_wait",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686083,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588084565,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588091186,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092744,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588093649,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588096446,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829731,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845018,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873032,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588098530,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914330,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579926483,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579956671,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580212235,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274530,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593061,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580612901,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667317,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580715595,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819702,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832756,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894399,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029627,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054361,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581145165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204025,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221908,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255969,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581264369,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312007,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315178,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322738,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443149,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472618,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524230,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529791,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537563,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546877,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550672,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:timerfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575988,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623217,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_filldir64",
        "fs/compat.c:compat_filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659665,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665634,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894510,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102990,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245979,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312776,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363406,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582457036,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582465590,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582482912,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582584962,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582976982,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018531,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675139,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584493735,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506580,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517646,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614702,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677057,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584696634,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:SyS_getrandom",
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712971,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584717672,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584995495,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585305329,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585602174,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585663129,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585673465,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585836987,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586336865,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399372,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586776451,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586801812,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586846544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852306,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586943774,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587143539,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587239019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587247096,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587438135,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587619942,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3333",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298158,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379785,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579403077,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434993,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459181,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306916,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671112,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588309854,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672131,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588311748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588314335,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588318487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319425,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321437,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829751,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848868,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885496,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324197,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579922279,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935288,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961176,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221798,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286825,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580623077,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641290,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700617,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706656,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580750295,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793113,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580860099,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875644,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939327,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581005528,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048619,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076251,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281143,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581192325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252914,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268891,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581313313,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363640,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368067,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373905,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497631,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527934,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577353,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582616,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590577,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600879,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609033,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611342,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622635,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713985,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722089,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581881168,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933722,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067126,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089011,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330970,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397525,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545595,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SYSC_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563316,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582676950,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026800,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070277,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238008,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583475373,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716531,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851068,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584562752,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571879,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585937,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597206,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584696390,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584759185,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778065,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799641,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080599,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396775,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585685710,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585749848,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585760621,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585923243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586299011,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586433778,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502766,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586896711,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586925580,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586973527,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975330,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587068868,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587273785,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284730,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381206,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587519600,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574694,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587772458,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:312",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858053,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318808,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408005,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579431119,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463290,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487421,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588872286,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579701864,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588875214,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait",
        "kernel/sched/wait_bit.c:atomic_t_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579702890,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877535,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879825,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588883426,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588884950,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588886485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869895,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889511,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579928657,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588890298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967619,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579980791,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580008192,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274470,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580340288,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703989,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724037,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786056,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580792178,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837543,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580882713,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951088,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970785,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039177,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118282,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159399,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846370,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322248,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384602,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407980,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444985,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581453487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505105,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509555,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515393,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639759,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670270,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721755,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727129,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735196,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753205,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756137,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767205,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781312,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859631,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867913,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582031225,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082586,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216577,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238620,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582481358,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548274,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684056,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695191,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715801,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582830502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192018,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583415392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583656347,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974129,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584114667,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584973616,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584983895,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584998023,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009429,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108906,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585179250,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198164,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219985,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503943,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585825825,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586117929,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586186923,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586198602,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586364123,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586762483,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586899639,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586969962,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587388151,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587417683,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587471747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587473534,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587570320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793813,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587804898,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587890893,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912303,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588042418,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588098553,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588298557,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:313",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578859836,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329396,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416829,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446239,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476663,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505277,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735987,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254345,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737018,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589255243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589258390,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589262197,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589263212,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589264747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579925267,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974449,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589268551,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014866,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031868,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580062151,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333618,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859384,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919322,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930031,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974183,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020739,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087216,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105314,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175209,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254095,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302587,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332224,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225498,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469841,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535192,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563241,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603541,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581613112,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661758,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673086,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801211,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833913,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890925,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897942,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902645,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913481,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921817,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929134,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939972,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953875,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039743,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050870,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582219527,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270630,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406656,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428443,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672310,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740268,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878266,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892192,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582915916,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583018501,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402992,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444196,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626220,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583874344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "lib/percpu_ida.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_ida.c:percpu_ida_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584314983,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585209624,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585217655,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585232327,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585243574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585344246,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415090,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585434319,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585452064,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748707,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072317,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454922,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623218,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/rtc/rtc-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587205140,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587264994,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587694335,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll",
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720263,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587776788,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587778551,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879255,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588136404,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588147505,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588238489,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588245773,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401432,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451792,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659310,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:341",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354689,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579479759,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510322,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539453,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492484,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579775667,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589496569,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776725,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589497435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589500734,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589504693,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589505724,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950964,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970546,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025745,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511111,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580062226,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580078748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580108471,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388538,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735887,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904741,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927912,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994910,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006604,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050855,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093107,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165136,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581185154,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255529,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337301,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386231,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416000,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468257,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554737,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621242,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648757,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688869,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699464,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748222,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754803,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759374,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888219,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921190,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581974397,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980127,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992972,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998804,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006185,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008775,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026388,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__x32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_compat_sys_io_getevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040067,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127903,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143334,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582314375,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369270,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505920,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527963,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774166,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798264,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844028,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984378,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000346,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583022396,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583134700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566180,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731384,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583839073,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331026,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410951,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585327757,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585336647,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351623,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585362998,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585467286,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585538690,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557743,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585575328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579964,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585881427,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216594,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586507640,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586594985,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602650,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586772098,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194368,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587403965,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587446363,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587824128,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587853335,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587908468,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587911161,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020741,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319156,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588330352,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588425177,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435828,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591304,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588644736,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588874365,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:350",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368353,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468524,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497767,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529916,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549837,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953482,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803319,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589957353,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589958802,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589961096,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589964973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862085,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589967877,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579989590,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009764,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589970293,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580105830,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122402,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580153550,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580441579,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580822698,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024381,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069354,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114427,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236085,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256089,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330330,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413758,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447950,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497765,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669304,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765333,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806981,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581817217,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865486,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877024,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582007795,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058443,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108009,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118509,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128867,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582147664,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582164767,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190984,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201265,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289922,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302254,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582482372,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537546,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948379,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972499,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019246,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181505,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583203037,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583322053,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710783,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756438,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583918156,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584029250,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526107,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584607340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585539701,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585549574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585564821,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585576587,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585683165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585758769,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585795476,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585800157,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118540,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586458861,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586752147,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587025640,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459941,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587675439,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587716172,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588126841,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157612,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588217484,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588219167,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334161,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588717337,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588732211,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588829064,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589002406,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589057232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589314401,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:355",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372593,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523767,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575965,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850887,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590185017,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852072,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590186466,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590188760,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590192637,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910783,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590195541,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580039718,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060814,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118072,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590197836,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154934,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580171565,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580201342,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258639,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580490597,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874023,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057333,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079725,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125322,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171387,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219356,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581294549,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314761,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389738,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474798,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486549,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512174,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562293,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594383,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156651,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741480,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837541,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581889777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937886,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941219,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949280,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136235,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582185524,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195741,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203974,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212642,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582220092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224864,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582241830,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282097,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316395,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388898,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401278,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582581604,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055035,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079107,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125438,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274894,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583287365,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308813,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583427381,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583820399,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866150,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584021413,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584133118,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167817,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584661227,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584745132,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585680613,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690454,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585705957,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585717547,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585744936,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585824157,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585900977,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585921194,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585938228,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942862,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266044,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586606272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586898611,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982608,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587044502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225439,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663061,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879745,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587920460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331609,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588362912,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588422252,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588423793,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540766,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588941193,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588955920,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589053567,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589070704,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589226806,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589281504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589538801,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866383,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:__syscall_return_slowpath",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555282,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611421,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591200286,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889399,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591203116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891031,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591203365,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591205021,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591208497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954809,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591211325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091218,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120461,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175000,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591213648,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580216100,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580235681,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580269793,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327823,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636800,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016883,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581239237,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263005,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363984,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403929,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484733,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507172,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586858,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654868,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691827,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721535,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772714,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808159,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174245,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962024,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027507,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060084,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112100,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117109,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169107,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172988,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582180589,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319605,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:wait_for_space",
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361459,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422745,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582442511,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449481,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582456963,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582465327,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476278,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539826,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560126,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker",
        "fs/io-wq.c:io_assign_current_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566752,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605050,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_skip",
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694713,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890275,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583374103,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445630,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602611,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616726,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639905,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783969,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215596,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584255714,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584411774,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584523315,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566070,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407044,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426534,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586434901,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476795,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551629,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586640001,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586656103,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:extract_crng_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586677316,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586682355,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034764,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587709827,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818850,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587829462,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875008,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079324,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588732481,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771864,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_bios_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195780,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224657,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wait_for_wmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289262,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291027,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832037,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589860827,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id",
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590009052,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590032013,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590199904,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590261961,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590541169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591084932,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:356",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579267379,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274440,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403262,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507089,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536546,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579591629,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591695363,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883863,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591698236,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885751,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591698512,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591700185,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591704424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942998,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591706573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074388,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101563,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580163679,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591708880,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220305,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252353,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642582,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020275,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313173,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449157,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633017,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769823,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797819,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855667,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591670086,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010920,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163477,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582219622,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227827,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582377519,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476729,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582490901,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497345,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506160,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513790,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582522588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532723,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582558810,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqpoll_wait_sq",
        "fs/io_uring.c:io_cqring_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630348,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748107,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_skip",
        "fs/coredump.c:dump_skip",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583490196,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737032,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583760984,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584374444,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584533706,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587176,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524615,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586541538,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549763,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586561837,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586589755,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663689,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586748761,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766679,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:extract_crng_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586786590,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586790756,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587118227,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587462743,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587770147,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587871202,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887215,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935453,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124237,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588555068,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588761473,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588791452,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193880,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589221543,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_wait_for_wmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287929,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589290085,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589868485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589891349,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589900762,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590051561,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590079187,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590250400,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590316217,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590600783,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071591126940,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591157350,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:362",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585952,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579268770,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276066,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406266,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572864,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591637878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893047,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591640748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894935,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591641024,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591642519,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591646455,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950730,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591649510,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075716,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106571,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167263,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591656256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205649,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257553,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580645286,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029667,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331691,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469999,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654694,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591614384,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796930,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825781,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886371,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246071,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253867,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402236,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503442,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518513,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582523841,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533933,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541561,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551363,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560451,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652712,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_cqring_wait"
      ],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread"
      ]
    },
    {
      "addr": 18446744071582659055,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511765,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747383,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763809,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785128,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584408892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566122,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465656,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409876,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586424514,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586434947,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446797,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586474232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586545081,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632185,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646279,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:extract_crng_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586667067,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586670913,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004627,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587344706,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587649393,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587754342,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587767039,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005654,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588438364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588646835,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588675761,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589087288,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181849,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589774485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589792634,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589807369,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589969976,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993621,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590168460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590231968,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590525999,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071591057317,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591092556,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:363",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586160,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071590511008,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310658,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317861,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468802,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579613058,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646832,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592811708,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007955,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592814669,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009726,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592814940,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592816405,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592819955,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580079711,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592823123,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580210116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580247069,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311902,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592829877,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580373922,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408801,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252373,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579338,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725047,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581922907,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592788102,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114842,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181059,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582347544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505349,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563911,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582571771,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725292,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818962,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833844,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839857,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849981,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857617,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867528,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877251,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974762,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sqd_handle_event",
        "fs/io_uring.c:io_sqd_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582983906,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583867082,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584109092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125587,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147791,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584804492,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584977041,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931896,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586936685,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586952786,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586960915,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586973037,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002600,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587083816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179401,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193632,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587215243,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587219713,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587571139,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587911095,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588236024,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588352330,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588363430,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620087,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105867,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589324627,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589363841,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589805208,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833789,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589903337,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589905172,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590533875,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590552730,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590569808,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590738136,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590766501,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014870,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198858,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591329905,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071591899912,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591932918,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:361",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591317584,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579368212,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376319,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545690,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705793,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579742886,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579758471,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594713631,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156306,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:do_wait_intr_irq",
        "kernel/sched/build_utility.c:do_wait_intr",
        "kernel/sched/build_utility.c:prepare_to_wait_event",
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:bit_wait_io",
        "kernel/sched/build_utility.c:bit_wait",
        "kernel/sched/build_utility.c:prepare_to_swait_event",
        "kernel/sched/build_utility.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594720089,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594724665,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594727614,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594730720,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580368950,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408191,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523742,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594738991,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589295,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640472,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/futex/requeue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/requeue.c:futex_wait_requeue_pi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580645161,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/futex/waitwake.c:futex_wait_multiple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042332,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/irq_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581543631,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949804,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101046,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329555,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594686966,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519990,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557539,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640770,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582821001,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031333,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093721,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268038,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_from_pipe_next",
        "fs/splice.c:splice_from_pipe_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376172,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583391130,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400466,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411238,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420023,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423774,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443718,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439782,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705507,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722943,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584746320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585709502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586016813,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io_uring.c:io_sqd_handle_event",
        "io_uring/io_uring.c:io_sqd_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586034212,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wqe_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134376,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587184889,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/pci/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588227623,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588242963,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256083,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588269305,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588301304,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588392061,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493017,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": [
        "drivers/char/random.c:try_to_generate_entropy"
      ]
    },
    {
      "addr": 18446744071588522991,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525697,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588906131,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589261821,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589729659,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761556,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590036323,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590552298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590796577,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841489,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591325468,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591357281,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591433285,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591435187,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592142489,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592165527,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592186344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592368317,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592399257,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592586782,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592661037,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592859290,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592999313,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071593619576,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_recvmsg",
        "net/xdp/xsk.c:xsk_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593657457,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:391",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495568,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071592988512,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579442180,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452639,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831349,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874566,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893031,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596460747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580337154,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:do_wait_intr_irq",
        "kernel/sched/build_utility.c:do_wait_intr",
        "kernel/sched/build_utility.c:prepare_to_wait_event",
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:bit_wait_io",
        "kernel/sched/build_utility.c:bit_wait",
        "kernel/sched/build_utility.c:prepare_to_swait_event",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596470310,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596475328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:___down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596479140,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596482497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580590237,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648861,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580779390,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596491183,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580827256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851279,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907032,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/futex/requeue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/requeue.c:futex_wait_requeue_pi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580911801,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/futex/waitwake.c:futex_wait_multiple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344939,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/irq_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914966,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369079,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:folio_wait_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524512,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575617,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705147,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582829478,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423558,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038201,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080266,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161510,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365833,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595605,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661721,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583849254,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_from_pipe_next",
        "fs/splice.c:splice_from_pipe_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961284,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583976746,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988546,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998390,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007484,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584012155,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035222,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585101022,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397480,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416015,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440987,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586257372,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454675,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_poll_classic",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782065,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_cqring_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819202,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sqd_handle_event",
        "io_uring/sqpoll.c:io_sqd_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870033,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wqe_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588336200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/pci/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589638130,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654578,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589669762,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589684169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589718760,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589816851,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936964,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589965871,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589969217,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590417731,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590823725,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348443,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591410996,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591639392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592206186,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592480527,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592531491,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593078524,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593111985,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593199509,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593201523,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593966807,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593992951,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594016873,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594216125,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594250441,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594451902,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594527507,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594737050,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594890881,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071595551795,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595587900,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594877104,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454285,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579464815,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664793,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880421,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923245,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942327,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580127832,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/vhost_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/vhost_task.c:vhost_task_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597002320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580404578,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:do_wait_intr_irq",
        "kernel/sched/build_utility.c:do_wait_intr",
        "kernel/sched/build_utility.c:prepare_to_wait_event",
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:bit_wait_io",
        "kernel/sched/build_utility.c:bit_wait",
        "kernel/sched/build_utility.c:prepare_to_swait_event",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597011939,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597016912,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:___down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597020681,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597024226,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580663757,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722381,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580862382,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597032602,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934975,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990898,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/futex/requeue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/requeue.c:futex_wait_requeue_pi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995705,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_wait",
        "kernel/futex/waitwake.c:futex_wait_multiple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439227,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/irq_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582097574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582573927,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:folio_wait_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728154,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785492,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919419,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583044750,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596963691,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246729,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583290805,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583377054,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585529,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583812373,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583878579,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886568,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584074554,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_from_pipe_next",
        "fs/splice.c:splice_from_pipe_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584184676,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202106,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210421,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584223062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584237451,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584259923,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330535,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628094,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585646478,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671733,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586497948,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586572161,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "crypto/jitterentropy-testing.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/jitterentropy-testing.c:jent_raw_hires_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697937,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_hctx_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587041515,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_cqring_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085618,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sqd_handle_event",
        "io_uring/sqpoll.c:io_sqd_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257285,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_signal_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588683448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/pci/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:do_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589958213,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973765,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589988777,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590023560,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590122675,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590238876,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590242932,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275263,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590278817,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590737235,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591165373,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591710171,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591826300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592630394,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592911468,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592961347,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593530112,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567128,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593659477,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593661536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594343735,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594370151,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594394089,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594603325,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594637145,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594843838,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594919132,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595129174,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595282710,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071596062326,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596096972,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:392",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595269456,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int signal_pending(struct task_struct * p)
```

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484205,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494879,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579699360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579922947,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962493,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981671,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__do_sys_pause"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580172312,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/vhost_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/vhost_task.c:vhost_task_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597931621,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461378,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:do_wait_intr_irq",
        "kernel/sched/build_utility.c:do_wait_intr",
        "kernel/sched/build_utility.c:prepare_to_wait_event",
        "kernel/sched/build_utility.c:bit_wait_io_timeout",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:bit_wait_io",
        "kernel/sched/build_utility.c:bit_wait",
        "kernel/sched/build_utility.c:prepare_to_swait_event",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597941283,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597946256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:___down_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597950025,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597953570,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580730416,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_wait_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952526,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597961994,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001352,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025999,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086535,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/futex/requeue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/requeue.c:futex_wait_requeue_pi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091665,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:__futex_wait",
        "kernel/futex/waitwake.c:futex_wait_multiple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548696,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/irq_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582235194,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743591,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:folio_wait_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897754,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960969,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093563,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583226573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597891495,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481257,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583520120,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616158,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583778521,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_reclaim",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_high_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018373,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084899,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584093736,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select",
        "fs/select.c:poll_select_finish"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584290666,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_to_socket",
        "fs/splice.c:splice_from_pipe_next",
        "fs/splice.c:splice_from_pipe_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584398660,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584416634,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424917,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437654,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584476707,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585565300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585874814,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585893214,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:__do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585918517,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:wq_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586768044,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586969185,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_hctx_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587314706,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_cqring_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365042,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sqpoll_wait_sq",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/sqpoll.c:io_sqd_handle_event",
        "io_uring/sqpoll.c:io_sqd_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587422725,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506485,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "rust/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "rust/helpers.c:rust_helper_signal_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588984056,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/pci/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590279776,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:iterate_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297238,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590312405,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590327305,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590362184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590462195,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_zero",
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590583956,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:write_pool_user",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/random.c:get_random_bytes_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590616143,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590619810,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591099203,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591511357,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592151740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/gpu/drm/drm_syncobj.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592454459,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_ring_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592574300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592800892,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593375210,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593660187,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593711475,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_bios_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594302640,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594339724,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594437413,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594439160,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595143497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595170967,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_timer_continue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595195385,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_phys_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595406978,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440457,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595654478,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595730714,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:inet_wait_for_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595945971,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596127621,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    },
    {
      "addr": 18446744071596925027,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596966655,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:384",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110288,
      "name": "signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490217412,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm64/kernel/ptrace.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490292904,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm64/kernel/sys_compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sys_compat.c:compat_arm_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490322444,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm64/kernel/armv8_deprecated.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/armv8_deprecated.c:emulate_swpX"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503955752,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490382356,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vcpu_check_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490445540,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490628848,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490662828,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490710752,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490738904,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__arm64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503924612,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491042064,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503928716,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491045792,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503929036,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:__wait_for_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503931404,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503937896,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491113300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503941432,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491240632,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491264284,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491331968,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503944680,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491374668,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491393416,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491439168,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491501440,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491767148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491825284,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492199200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492415628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492442360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:wait_on_page_bit_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492496556,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492551212,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492604464,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492701048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492721636,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492795052,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492885828,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492904780,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492934596,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492995584,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493033852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493194536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493301572,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357000,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493367824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493424180,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493432968,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493444796,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493626936,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493681404,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493744476,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493758276,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493770704,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493777032,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493786240,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493789724,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493813144,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents_time32",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849844,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493855852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493896048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493987956,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494003704,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494230640,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494290792,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494432016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494469280,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494752880,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494784360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494835200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495004872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495023628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495047772,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495218972,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495626976,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495683852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495847804,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495982980,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496020656,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496910220,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497008476,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498356604,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498376696,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498387424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498408700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498449200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498540948,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498719996,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498744628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498772124,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499089928,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499248780,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/misc/vexpress-syscfg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499491964,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499856456,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499975824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500117768,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500320372,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500815852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501087688,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501151872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501825808,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501867780,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501939592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501941716,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502076068,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502539400,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502557296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502664740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502676460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502845072,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502916080,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503206784,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224424836,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm/kernel/ptrace.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3224435556,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:arm_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 3224461228,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm/kernel/swp_emulate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236559256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3224530620,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3224706328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224738544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3224771756,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3224790480,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 3236534360,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 3225051324,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3236538436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3225053356,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3236539092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 3236542876,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236547904,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 3225116124,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 3236550676,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225253148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 3225276160,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 3225325652,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 3236553708,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 3225375232,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 3225391352,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 3225429592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3225483004,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225715536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225794448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3226096620,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3226299260,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226318952,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 3226370020,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226431572,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226459872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 3226539156,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:compact_unlock_should_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 3226552224,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226610668,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 3226684704,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226696272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226722372,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 3226750340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226826508,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878452,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226905528,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226946104,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 3226954908,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227005244,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227010804,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227016140,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 3227161816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227213668,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3227267900,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227275252,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227281076,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227291300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227299688,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227301876,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 3227327580,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_getevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents"
      ],
      "caller_func": []
    },
    {
      "addr": 3227350216,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3227375564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3227453180,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 3227467940,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227659968,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227723312,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 3227866440,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3227905728,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3228204792,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228254492,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228416692,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 3228431316,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 3228447060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228594920,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3228984988,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 3229034296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229201080,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229323672,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 3229364244,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 3230185920,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3231043184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3231052704,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3231068864,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 3231080512,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 3231112748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 3231197788,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 3231346832,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3231360460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3231386292,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3231641596,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3231753520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/misc/vexpress-syscfg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 3231964720,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3232290412,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3232521740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232615724,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232781392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3233321656,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3233626504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3233665532,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234363004,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "sound/core/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/control.c:snd_ctl_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234391216,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "sound/core/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/timer.c:snd_timer_user_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234408948,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "sound/core/pcm_native.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/pcm_native.c:snd_pcm_drain"
      ],
      "caller_func": []
    },
    {
      "addr": 3234440028,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "sound/core/pcm_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/pcm_lib.c:__snd_pcm_lib_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 3234608252,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 3234636004,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234696928,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 3234698756,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3234827604,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 3235247576,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235263916,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3235367508,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 3235380392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3235554164,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235610228,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235881676,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282267592,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave",
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282715152,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283446588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283487056,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283534260,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283562772,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297771496,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283921296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297776976,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283923224,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297777988,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297783504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297790564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284004948,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297794008,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284141884,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284173408,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284260576,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297797660,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284315444,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284336104,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284386224,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284461088,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284811320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284897748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285417684,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285682456,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285716872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285784376,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285853688,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285922880,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286035180,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286066260,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286166236,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286282844,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286307696,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286344816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286420396,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286467116,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286556824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286696208,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286799520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286841148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286899792,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286914208,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286982060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286989392,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286999976,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287209952,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287283880,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287358816,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287367196,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287374784,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287389268,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287400448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287409980,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ctx_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287429512,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__se_compat_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287466568,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287483732,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287532744,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287633340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287654096,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287928344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288004712,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288180436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288226576,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288583368,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288618520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288681812,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288889084,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288908820,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288937416,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289127500,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289751192,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289826368,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290048688,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290208076,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290254284,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291004532,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291084796,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291539032,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291552436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291574712,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291593416,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291635184,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291772292,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291872328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291897248,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291932568,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292271840,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292776648,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293178680,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293320596,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293334268,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293376112,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293627268,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294275764,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294611076,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294663588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295227176,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295278584,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295360544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295362872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295527460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296113824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296136036,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296271804,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296285944,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296496608,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296580588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296944092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271344826,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_exit",
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271359060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271383878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271406570,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271432456,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271458048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigsuspend",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279793570,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271642056,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279796882,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271643682,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279797632,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279801086,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279804574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271691220,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279806454,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271769766,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271793448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271833902,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279808548,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271864944,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271875334,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271897014,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272086544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272147708,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272349966,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272518924,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272558364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272597398,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272635578,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272702368,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714766,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272764070,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272826060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272829428,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272852980,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272898740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272906472,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272974564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024558,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273045554,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273079374,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273087494,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273127128,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273130296,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273134210,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273266764,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273304992,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273351478,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273359672,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273363894,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273371780,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273378448,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273382856,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273401166,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273420222,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273425090,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273454490,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273505668,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273518322,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273684002,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273733942,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273844812,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273874630,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274095986,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274116332,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274158300,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274293460,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274305954,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274320702,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274437986,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274784414,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274832092,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274981228,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275082736,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275112520,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275597540,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275671486,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276034878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276043838,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276055514,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276066628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276093320,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276160102,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276233298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276243198,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276265956,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276708356,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276967410,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277055502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277070976,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277217124,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277634702,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277811190,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277863484,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278172064,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278195718,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278246660,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278247968,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278352736,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278704266,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278717130,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278803748,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278815824,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278957888,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279006606,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279245988,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468256,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497431,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552269,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783307,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823239,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787305,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824424,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589788754,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589791048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589794925,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882895,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797829,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580008454,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580029550,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087272,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589800124,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580124134,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140765,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170142,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580227439,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459397,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518000,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842823,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026181,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048573,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094170,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140235,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188204,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263397,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283609,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358586,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443646,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581455397,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480910,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531029,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563119,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758939,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710216,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806277,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581858513,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906622,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909955,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054483,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104971,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154260,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582164477,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172710,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181378,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188828,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582193600,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582210566,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223100,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250833,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285131,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357634,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370014,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582550340,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607226,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767901,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583023771,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047843,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094174,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243630,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256101,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277549,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583396117,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789135,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583834886,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583990149,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584101854,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136553,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611691,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584693948,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585441637,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585451478,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466981,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585478571,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585505960,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585585149,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585661969,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585682170,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585699204,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703838,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029292,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296752,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459521,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_wait_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586655699,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586739616,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759840,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931519,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587346821,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510721,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587551436,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587938393,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587969696,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029036,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588030577,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588147502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547577,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562304,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659951,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588677088,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588833190,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588887680,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589143169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855313,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298964,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397178,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426311,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461158,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589505798,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757847,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509849,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511276,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513528,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589517847,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817871,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589520271,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947126,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968019,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032616,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589522572,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069430,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086173,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580120670,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580174927,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406453,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466048,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580788999,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972277,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995853,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041338,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087179,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134956,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210053,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229618,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302298,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386030,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397648,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423231,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472853,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504735,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589483163,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649144,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714016,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743941,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785973,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581796113,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844206,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847539,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855600,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992035,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042411,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101917,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105361,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118998,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126368,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131098,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582147142,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582160940,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188561,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222891,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295346,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307710,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582487508,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544394,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671477,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705069,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960923,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984995,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031326,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180782,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193253,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214685,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583333205,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726191,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771942,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583926005,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584037534,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072115,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584541515,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624716,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585311669,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585321510,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337013,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585348507,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375784,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585450445,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585521889,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585542042,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558542,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585563038,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585875308,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586138128,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335761,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_wait_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524035,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586606832,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586665072,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692422,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872671,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115119,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587278881,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319532,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587651497,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682800,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742124,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587743665,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587860334,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259561,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274288,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588371935,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588389072,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588545126,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588599616,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588868161,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862209,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368417,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468176,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497351,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529644,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549549,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226715,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811255,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590230713,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812440,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590232162,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590234456,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590238333,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871055,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590241237,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999990,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021086,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580078344,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590243532,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580115206,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580131837,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580161614,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218911,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450645,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580509248,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834071,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017381,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039773,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085370,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131435,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179404,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254597,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274809,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349786,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434846,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446597,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472222,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522341,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554431,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202347,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701528,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767164,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797589,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839621,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581849825,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897934,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901267,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909328,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045763,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095451,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154957,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163190,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171858,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582179308,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184080,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201046,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582213580,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582241313,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275611,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348114,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360494,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582540452,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582597338,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758141,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012379,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036451,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082782,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583227662,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240133,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261581,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583379893,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583772895,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818646,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583973909,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584085614,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120313,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611387,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584695292,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585631013,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585640854,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585656357,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585667947,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695336,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774557,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851377,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871594,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585888244,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585892878,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216060,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586554240,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586853171,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586937168,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586957376,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179999,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587614309,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587835889,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587876604,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588270169,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588301472,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360812,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588362353,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479326,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879753,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894480,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907459,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netfilter/nfnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589096127,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589113264,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589269366,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589324064,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589580033,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862526,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376862,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499911,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579529942,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563287,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_peek_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582685,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__x64_sys_pause",
        "kernel/signal.c:__set_task_blocked",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:retarget_shared_pending",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590277069,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856407,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait.c:do_wait_intr_irq",
        "kernel/sched/wait.c:do_wait_intr",
        "kernel/sched/wait.c:prepare_to_wait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590281305,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/wait_bit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/wait_bit.c:bit_wait_io_timeout",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/wait_bit.c:bit_wait_io",
        "kernel/sched/wait_bit.c:bit_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579857800,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/swait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:prepare_to_swait_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590281830,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590284686,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590289172,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/semaphore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579916564,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590291581,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:__rt_mutex_slowlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046925,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066530,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580126872,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:msleep_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590293852,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167046,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580183574,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580215740,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271679,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580506281,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565584,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892391,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078693,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101401,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147293,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193899,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581242608,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318437,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338684,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413722,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499342,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511061,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537051,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587294,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619487,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:unmerge_ksm_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252747,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768728,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "mm/memcontrol.c:mem_cgroup_resize_max",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835853,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866757,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909165,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581919329,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:wait_for_partner",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967549,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970883,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978955,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:do_sys_poll",
        "fs/select.c:core_sys_select",
        "fs/select.c:do_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117443,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_file_splice_write",
        "fs/splice.c:__splice_from_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168301,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582217106,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582225676,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231502,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247121,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/signalfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:signalfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255271,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_write",
        "fs/eventfd.c:eventfd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582258096,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582278950,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents_time32",
        "fs/aio.c:__x64_sys_io_getevents_time32",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_getevents",
        "fs/aio.c:__x64_sys_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291612,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320945,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354171,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427698,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_emit",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440190,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582621588,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679402,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808981,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843057,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101558,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125587,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172062,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583320401,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331971,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:do_semtimedop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583355324,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583476916,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873887,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919718,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "crypto/algboss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algboss.c:cryptomgr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584077717,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584188441,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215253,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719083,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584802940,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585736544,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585748982,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_write",
        "drivers/tty/n_tty.c:n_tty_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585764469,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:set_termiox"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585776059,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_block_til_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585803352,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/vt/selection.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/selection.c:paste_selection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585883933,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585958975,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:read_iter_zero",
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585979526,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:urandom_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585996200,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000862,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/char/hw_random/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hw_random/core.c:rng_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325164,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_get_wakeup_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586666304,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959283,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587045628,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_do_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587065504,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587106230,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_del_group_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587287135,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:reap_as"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587725536,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587949553,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587992156,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wait_for_completion",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588405449,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:sock_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588436800,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_alloc_send_pskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496364,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588497908,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588616238,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021817,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_attachskb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589036700,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135887,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589153088,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_splice_read",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589303148,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__skb_recv_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589365936,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_stream_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589626563,
      "name": "signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:347",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int signal_pending(struct task_struct * p)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
