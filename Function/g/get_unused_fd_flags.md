# Function: <code>get_unused_fd_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116544,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:559",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:SyS_dup",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "net/socket.c:sock_map_fd",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116544,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282272,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:560",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:SyS_dup",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282272,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360704,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:560",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:SyS_dup",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360704,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415968,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:546",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:SyS_dup",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415968,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557584,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:547",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:SyS_dup",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557584,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714352,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:542",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714352,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801072,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:542",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/fhandle.c:do_handle_open",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801072,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919872,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919872,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992256,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992256,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227364,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:548",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/pid.c:pidfd_getfd",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:__scm_install_fd",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226112,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272715,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:533",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271856,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582297742,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:533",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297504,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582616558,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:533",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616448,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583151155,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:562",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151056,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583724787,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:562",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724672,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583941843,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:562",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl",
        "net/handshake/netlink.c:handshake_nl_accept_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941728,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584149003,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:562",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_create_getfd",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl",
        "net/handshake/netlink.c:handshake_nl_accept_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147328,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493507080,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__arm64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493507080,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227063840,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "ipc/mqueue.c:__se_sys_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227063840,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287070816,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287070816,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273179330,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "ipc/mqueue.c:__se_sys_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273179330,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960992,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960992,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898560,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898560,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952304,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952304,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int get_unused_fd_flags(unsigned int flags)
```

```json
{
  "name": "get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022496,
      "name": "get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/file.c:ksys_dup",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022496,
      "name": "get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
