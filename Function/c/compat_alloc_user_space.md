# Function: <code>compat_alloc_user_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959440,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:1161",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/compat.c:compat_convert_timespec",
        "kernel/compat.c:compat_SyS_timer_create",
        "kernel/compat.c:compat_SyS_move_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "mm/mempolicy.c:compat_SyS_get_mempolicy",
        "mm/mempolicy.c:compat_SyS_set_mempolicy",
        "mm/mempolicy.c:compat_SyS_mbind",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/compat.c:compat_SyS_io_getevents",
        "fs/compat.c:compat_SyS_io_submit",
        "fs/compat.c:compat_SyS_io_submit",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat_mq.c:compat_SyS_mq_open",
        "ipc/compat_mq.c:compat_SyS_mq_notify",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_sock_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959440,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990256,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:1161",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_migrate_pages",
        "kernel/compat.c:compat_SyS_move_pages",
        "kernel/compat.c:compat_SyS_timer_create",
        "kernel/compat.c:compat_convert_timespec",
        "mm/mempolicy.c:compat_SyS_mbind",
        "mm/mempolicy.c:compat_SyS_set_mempolicy",
        "mm/mempolicy.c:compat_SyS_get_mempolicy",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/compat.c:compat_SyS_io_submit",
        "fs/compat.c:compat_SyS_io_submit",
        "fs/compat.c:compat_SyS_io_getevents",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "ipc/compat_mq.c:compat_SyS_mq_notify",
        "ipc/compat_mq.c:compat_SyS_mq_open",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990256,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020784,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:1169",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_move_pages",
        "kernel/compat.c:compat_SyS_timer_create",
        "kernel/compat.c:compat_convert_timespec",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr",
        "ipc/compat_mq.c:compat_SyS_mq_notify",
        "ipc/compat_mq.c:compat_SyS_mq_open",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020784,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026704,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:609",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_move_pages",
        "kernel/compat.c:compat_convert_timespec",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:C_SYSC_msgctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:do_compat_semctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026704,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073712,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:569",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:C_SYSC_migrate_pages",
        "kernel/compat.c:compat_SyS_move_pages",
        "mm/mempolicy.c:C_SYSC_mbind",
        "mm/mempolicy.c:C_SYSC_set_mempolicy",
        "mm/mempolicy.c:C_SYSC_get_mempolicy",
        "fs/splice.c:compat_SyS_vmsplice",
        "fs/signalfd.c:compat_SyS_signalfd",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:compat_SyS_io_submit",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_ifr_data_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073712,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133040,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:460",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133040,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180256,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:429",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180256,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226288,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226288,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274496,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274496,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342896,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:277",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342896,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328016,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:277",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "net/socket.c:compat_ifreq_ioctl",
        "net/socket.c:ethtool_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328016,
      "name": "compat_alloc_user_space",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331312,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:277",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:ethtool_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331312,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491513768,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_compat_sys_mbind",
        "mm/mempolicy.c:__arm64_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy",
        "mm/migrate.c:__arm64_compat_sys_move_pages",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491513768,
      "name": "compat_alloc_user_space",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284483424,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__se_compat_sys_kexec_load",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_compat_sys_mbind",
        "mm/mempolicy.c:__se_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__se_compat_sys_get_mempolicy",
        "mm/migrate.c:__se_compat_sys_move_pages",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:mt_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkpg_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_bulk_compat",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284483424,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243296,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243296,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190848,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190848,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580234544,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234544,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * compat_alloc_user_space(long unsigned int len)
```

```json
{
  "name": "compat_alloc_user_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287536,
      "name": "compat_alloc_user_space",
      "external": true,
      "loc": "kernel/compat.c:365",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__do_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__do_compat_sys_get_mempolicy",
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:get_compat_bpf_fprog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287536,
      "name": "compat_alloc_user_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * compat_alloc_user_space(long unsigned int len)
```
</details>
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
