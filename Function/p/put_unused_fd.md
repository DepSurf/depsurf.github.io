# Function: <code>put_unused_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113136,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:573",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "net/socket.c:sock_map_fd",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113136,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278848,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:574",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278848,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357296,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:574",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:SyS_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:SYSC_accept4",
        "net/socket.c:sock_map_fd",
        "net/core/scm.c:scm_detach_fds",
        "net/compat.c:scm_detach_fds_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357296,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412608,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:560",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
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
      "addr": 18446744071581412608,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554224,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:561",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:SyS_eventfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SYSC_accept4",
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
      "addr": 18446744071581554224,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711264,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:556",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581711264,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797776,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:556",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581797776,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916624,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581916624,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989008,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581989008,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222752,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:562",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071582222752,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270272,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:547",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/file.c:__receive_fd",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270272,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295776,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:547",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/file.c:__receive_fd",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_openat2",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295776,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614656,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:547",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__do_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614656,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583147680,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:576",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_openat2",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147680,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722320,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:576",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722320,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939360,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:576",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd_secure",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/sock.c:sk_getsockopt",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939360,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145632,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:576",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_create_getfd",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/core/sock.c:sk_getsockopt",
        "net/unix/af_unix.c:unix_ioctl",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/handshake/netlink.c:handshake_nl_accept_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145632,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493502624,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__arm64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446603336493502624,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227061408,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "ipc/mqueue.c:__se_sys_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 3227061408,
      "name": "put_unused_fd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287067056,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 13835058055287067056,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273175288,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__se_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:__se_sys_open_by_handle_at",
        "ipc/mqueue.c:__se_sys_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446743936273175288,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957744,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581957744,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895312,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581895312,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949056,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071581949056,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void put_unused_fd(unsigned int fd)
```

```json
{
  "name": "put_unused_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018192,
      "name": "put_unused_fd",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_accept4",
        "net/socket.c:__sys_socketpair",
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
      "addr": 18446744071582018192,
      "name": "put_unused_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
