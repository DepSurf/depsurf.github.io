# Function: <code>fget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113520,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:716",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "mm/mmap.c:SyS_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:do_io_submit",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113520,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279248,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:717",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "mm/mmap.c:SyS_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:do_io_submit",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279248,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357696,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:717",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "mm/mmap.c:SyS_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:do_io_submit",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357696,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412864,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:703",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "mm/mmap.c:SyS_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:do_io_submit",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412864,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554480,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:706",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "mm/mmap.c:SyS_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:do_io_submit",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554480,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710512,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:702",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:aio_prep_rw",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710512,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797024,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:732",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:io_submit_one",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797024,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915856,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915856,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988240,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988240,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222448,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:751",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222448,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269968,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:851",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269968,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295472,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:863",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295472,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614352,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:923",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get_normal",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_get_tree",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614352,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149168,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:925",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_get_tree",
        "io_uring/io_uring.c:io_ringfd_register",
        "io_uring/io_uring.c:__io_sqe_files_update",
        "io_uring/io_uring.c:io_sqe_files_register",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/io_uring.c:io_files_update",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149168,
      "name": "fget",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721952,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:925",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_set_attribute",
        "kernel/nsproxy.c:__do_sys_setns",
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_get_tree",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721952,
      "name": "fget",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938992,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:926",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/fuse/inode.c:fuse_get_tree",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938992,
      "name": "fget",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584148224,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:1048",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/fuse/inode.c:fuse_get_tree",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_file_get_normal",
        "io_uring/tctx.c:io_ringfd_register",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/rsrc.c:io_sqe_files_register",
        "io_uring/rsrc.c:io_files_update",
        "io_uring/rsrc.c:__io_sqe_files_update",
        "io_uring/register.c:__do_sys_io_uring_register",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:set_bitmap_file",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148224,
      "name": "fget",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493501944,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:io_submit_one",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493501944,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227060536,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-clock.c:get_clock_desc",
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227060536,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287063616,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/aio.c:io_submit_one",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287063616,
      "name": "fget",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273174098,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273174098,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956976,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956976,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894544,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894544,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948288,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948288,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct file * fget(unsigned int fd)
```

```json
{
  "name": "fget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020432,
      "name": "fget",
      "external": true,
      "loc": "fs/file.c:738",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_get",
        "mm/mmap.c:ksys_mmap_pgoff",
        "fs/nsfs.c:proc_ns_fget",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/eventfd.c:eventfd_fget",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_submit_sqe",
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/inode.c:fuse_fill_super",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/dma-buf/dma-buf.c:dma_buf_get",
        "drivers/dma-buf/sync_file.c:sync_file_fdget",
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/net/ppp/ppp_generic.c:ppp_nl_newlink",
        "drivers/md/md.c:md_ioctl",
        "net/socket.c:sockfd_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020432,
      "name": "fget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
