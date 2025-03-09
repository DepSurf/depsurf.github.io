# Function: <code>anon_inode_getfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581298176,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298176,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581464384,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464384,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545136,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545136,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581599056,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599056,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743392,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/eventpoll.c:SyS_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/userfaultfd.c:SyS_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_read",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743392,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911968,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911968,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581996464,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:70",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/dma-buf.c:dma_buf_export",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996464,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133024,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133024,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582210176,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210176,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582446672,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:init_listener",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446672,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582503344,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:init_listener",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503344,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531072,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531072,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847136,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_get_device_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847136,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408800,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_device_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408800,
      "name": "anon_inode_getfile",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995728,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995728,
      "name": "anon_inode_getfile",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584220400,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220400,
      "name": "anon_inode_getfile",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434944,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:143",
      "file": "fs/anon_inodes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__pidfd_prepare",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/eventfd.c:do_eventfd",
        "drivers/gpio/gpiolib-cdev.c:lineevent_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/gpu/drm/drm_file.c:mock_drm_getfile",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434944,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493773392,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493773392,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227289240,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227289240,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287386000,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287386000,
      "name": "anon_inode_getfile",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273370228,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273370228,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178912,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178912,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582116544,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116544,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582169392,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169392,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct file * anon_inode_getfile(const char * name, const struct file_operations * fops, void * priv, int flags)
```

```json
{
  "name": "anon_inode_getfile",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245600,
      "name": "anon_inode_getfile",
      "external": true,
      "loc": "fs/anon_inodes.c:74",
      "file": "fs/anon_inodes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/eventpoll.c:do_epoll_create",
        "fs/anon_inodes.c:anon_inode_getfd",
        "fs/io_uring.c:io_uring_create",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/dma-buf/sync_file.c:sync_file_alloc",
        "drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245600,
      "name": "anon_inode_getfile",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
