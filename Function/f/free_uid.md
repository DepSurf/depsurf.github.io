# Function: <code>free_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420544,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:157",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:SyS_setpriority",
        "kernel/sys.c:SyS_getpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:__prog_put_common",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:free_pipe_info",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/eventpoll.c:ep_free",
        "fs/eventpoll.c:ep_alloc",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_get",
        "net/core/scm.c:__scm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420544,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432944,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:157",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/eventpoll.c:ep_alloc",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/scm.c:__scm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432944,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453296,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:157",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/eventpoll.c:ep_alloc",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/scm.c:__scm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453296,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441248,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:158",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/eventpoll.c:ep_alloc",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/scm.c:__scm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441248,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469552,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:SyS_getpriority",
        "kernel/sys.c:SyS_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init",
        "fs/eventpoll.c:ep_alloc",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:SyS_ioprio_get",
        "block/ioprio.c:SyS_ioprio_set",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/scm.c:__scm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469552,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483696,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:165",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483696,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516976,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:165",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_precharge_memlock",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516976,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536656,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536656,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562720,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562720,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594736,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:set_user",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594736,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574704,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:set_user",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_free",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574704,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580400,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:set_user",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580400,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654544,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:178",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "net/core/skbuff.c:msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654544,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579750272,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:178",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750272,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881856,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:178",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881856,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931008,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:178",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_clear_and_put",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931008,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970320,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:191",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "kernel/events/core.c:perf_mmap_close",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/eventpoll.c:eventpoll_release_file",
        "fs/eventpoll.c:ep_clear_and_put",
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:__msg_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970320,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490722216,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__arm64_sys_getpriority",
        "kernel/sys.c:__arm64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__arm64_sys_ioprio_get",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490722216,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224777724,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:set_user",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_unaccount_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224777724,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283544816,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_unaccount_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283544816,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271437376,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__se_sys_ioprio_get",
        "block/ioprio.c:__se_sys_ioprio_set",
        "net/core/skbuff.c:sock_zerocopy_callback",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271437376,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539024,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539024,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579467792,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467792,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536304,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536304,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void free_uid(struct user_struct * up)
```

```json
{
  "name": "free_uid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569328,
      "name": "free_uid",
      "external": true,
      "loc": "kernel/user.c:164",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority",
        "kernel/cred.c:put_cred_rcu",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_map_charge_init",
        "kernel/events/core.c:perf_mmap_close",
        "mm/mlock.c:user_shm_unlock",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventpoll.c:ep_free",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/scm.c:__scm_destroy",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569328,
      "name": "free_uid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
