# Function: <code>__refrigerator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802368,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:wait_port_writable",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802368,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830352,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830352,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859376,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859376,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867264,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867264,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910960,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910960,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955504,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:59",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955504,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002160,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:61",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002160,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044928,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:62",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044928,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094016,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094016,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156416,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156416,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140912,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140912,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145616,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145616,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289376,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289376,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497648,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/coredump.c:coredump_wait",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_data_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497648,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749936,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:62",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749936,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832480,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:62",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832480,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921968,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:62",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/signal.c:get_signal",
        "kernel/umh.c:usermodehelper_read_trylock",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "fs/jbd2/journal.c:kjournald2",
        "drivers/tty/hvc/hvc_console.c:khvcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921968,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491302968,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491302968,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225301144,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225301144,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284227872,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284227872,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271814144,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271814144,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063216,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063216,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008064,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008064,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054288,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054288,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop)
```

```json
{
  "name": "__refrigerator",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105072,
      "name": "__refrigerator",
      "external": true,
      "loc": "kernel/freezer.c:56",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
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
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/freezer.c:set_freezable",
        "kernel/time/hrtimer.c:do_nanosleep",
        "kernel/futex.c:futex_wait_queue_me",
        "kernel/audit.c:kauditd_thread",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/coredump.c:do_coredump",
        "fs/jbd2/journal.c:kjournald2",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105072,
      "name": "__refrigerator",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
