# Function: <code>wake_up_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551696,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2071",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:prepare_signal",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/fence.c:fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551696,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562224,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2160",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/fence.c:fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562224,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587120,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2170",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587120,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571376,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2137",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571376,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601120,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2156",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601120,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632608,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2152",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632608,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670352,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2146",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670352,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702144,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2552",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702144,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743024,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743024,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779504,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2828",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779504,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769840,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:3537",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769840,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777536,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:3558",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/io-wq.c:io_wq_worker_cancel",
        "fs/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777536,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870816,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:4173",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/io-wq.c:io_wq_worker_cancel",
        "fs/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870816,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986832,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:4292",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/build_utility.c:swake_up_all",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/userfaultfd.c:userfaultfd_wake_function",
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986832,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148080,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:4406",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/build_utility.c:swake_up_all",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/userfaultfd.c:userfaultfd_wake_function",
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148080,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226144,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:4483",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/build_utility.c:swake_up_all",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/userfaultfd.c:userfaultfd_wake_function",
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226144,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274928,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:4505",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_unfreeze_traced",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/task_work.c:task_work_add",
        "kernel/task_work.c:task_work_add",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/build_utility.c:swake_up_all",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:__thaw_task",
        "kernel/freezer.c:freeze_task",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/filemap.c:wake_page_function",
        "fs/userfaultfd.c:userfaultfd_wake_function",
        "io_uring/io-wq.c:io_wq_worker_cancel",
        "io_uring/io-wq.c:io_wq_worker_wake",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274928,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490921976,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490921976,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224938936,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224938936,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283772480,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283772480,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271558302,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271558302,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719648,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719648,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579647536,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579647536,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706912,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706912,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int wake_up_state(struct task_struct * p, unsigned int state)
```

```json
{
  "name": "wake_up_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750608,
      "name": "wake_up_state",
      "external": true,
      "loc": "kernel/sched/core.c:2672",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/kthread.c:kthread_unpark",
        "kernel/sched/swait.c:swake_up_all",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/freezer.c:freeze_task",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750608,
      "name": "wake_up_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
