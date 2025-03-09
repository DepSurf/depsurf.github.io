# Function: <code>fd_install</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581116832,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:624",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:SyS_dup",
        "fs/file.c:f_dupfd"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
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
      "addr": 18446744071581116832,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581284265,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:625",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581282560,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581362681,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:625",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581360976,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581417972,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581416240,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581559540,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:615",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:SyS_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/shmem.c:SyS_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:SyS_pipe",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581557776,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715604,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:610",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
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
      "addr": 18446744071581714544,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581802324,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:610",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/nsfs.c:open_related_ns",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
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
      "addr": 18446744071581801264,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581921173,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581920080,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581993557,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581992464,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227605,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:616",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/pid.c:pidfd_getfd",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
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
      "addr": 18446744071582226368,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272496,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:573",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd",
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
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_open_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272496,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296448,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:573",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd",
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
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296448,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:573",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd",
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
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592230347,
      "name": "fd_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582615344,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:602",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd",
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
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_openat2",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl",
        "net/socket.c:__sys_accept4_file",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/unix/af_unix.c:unix_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594010318,
      "name": "fd_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583148800,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:602",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd",
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
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
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
      "addr": 18446744071596051308,
      "name": "fd_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583721168,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:602",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
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
      "addr": 18446744071596573866,
      "name": "fd_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583938192,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:602",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/secretmem.c:__ia32_sys_memfd_secret",
        "mm/secretmem.c:__x64_sys_memfd_secret",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/open.c:do_sys_openat2",
        "fs/exec.c:begin_new_exec",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
        "fs/file.c:f_dupfd",
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree",
        "fs/nsfs.c:open_related_ns",
        "fs/init.c:init_dup",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_create_getfd",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/fhandle.c:do_handle_open",
        "ipc/mqueue.c:do_mq_open",
        "io_uring/io_uring.c:io_uring_create",
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/tty/pty.c:ptm_open_peer",
        "drivers/dma-buf/dma-buf.c:dma_buf_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sw_sync.c:sw_sync_ioctl",
        "drivers/gpu/drm/drm_atomic_uapi.c:drm_mode_atomic_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd",
        "net/socket.c:__sys_accept4",
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
      "addr": 18446744071597478404,
      "name": "fd_install.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584144800,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493509124,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__arm64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446603336493507360,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227065560,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 3227064080,
      "name": "fd_install",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287073156,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 13835058055287071120,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273181220,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__se_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446743936273179576,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581962293,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581961200,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899861,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581898768,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581953605,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071581952512,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void fd_install(unsigned int fd, struct file * file)
```

```json
{
  "name": "fd_install",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023861,
      "name": "fd_install",
      "external": true,
      "loc": "fs/file.c:611",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "fs/open.c:do_sys_open",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe2",
        "fs/pipe.c:do_pipe_flags",
        "fs/pipe.c:do_pipe_flags",
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
      "addr": 18446744071582022736,
      "name": "fd_install",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
