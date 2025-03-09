# Function: <code>freezing_slow_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579802256,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:__refrigerator",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/audit.c:kauditd_thread",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802256,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579830256,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830256,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579859280,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859280,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867168,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/kmod.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/freezer.c:freezer_read",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867168,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579910864,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910864,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579955408,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:40",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955408,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002064,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:42",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002064,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044832,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:43",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044832,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580093920,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093920,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580156304,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:wait_for_vfork_done",
        "kernel/exit.c:exit_mm",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156304,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580140800,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/fork.c:wait_for_vfork_done",
        "kernel/exit.c:exit_mm",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140800,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580145504,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:exit_mm",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:dump_interrupted",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145504,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580289285,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:exit_mm",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:dump_interrupted",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150861,
      "name": "freezing_slow_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580289248,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/fork.c:kernel_clone",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:dump_interrupted",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593925806,
      "name": "freezing_slow_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580497488,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:38",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:dump_interrupted",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994255,
      "name": "freezing_slow_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580749760,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:38",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:dump_interrupted",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596512553,
      "name": "freezing_slow_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580832304,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:38",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/ksm.c:ksm_scan_thread",
        "fs/coredump.c:dump_interrupted",
        "fs/ext4/mballoc.c:ext4_trim_interrupted",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411754,
      "name": "freezing_slow_path.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580921792,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491302832,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491302832,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225301008,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_do_scan",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225301008,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284227632,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:kopald",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284227632,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271814032,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_do_scan",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271814032,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580063120,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063120,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580007968,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007968,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054192,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054192,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool freezing_slow_path(struct task_struct * p)
```

```json
{
  "name": "freezing_slow_path",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580104976,
      "name": "freezing_slow_path",
      "external": true,
      "loc": "kernel/freezer.c:37",
      "file": "kernel/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/freezer.c:set_freezable",
        "kernel/freezer.c:freeze_task",
        "kernel/freezer.c:__refrigerator",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/cgroup/legacy_freezer.c:update_if_frozen",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104976,
      "name": "freezing_slow_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
