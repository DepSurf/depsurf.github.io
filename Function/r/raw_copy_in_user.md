# Function: <code>raw_copy_in_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581680391,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751865,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583385622,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996992,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585923825,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586905500,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587210185,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:165",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581825586,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581898985,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564969,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584212902,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586364705,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397401,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587724570,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:166",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998054,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582083102,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780883,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432948,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623854,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695665,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588059386,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582086595,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177230,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860947,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529807,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586772734,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587831207,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588235217,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582250098,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340366,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584051417,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584727143,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027187,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588134145,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588627182,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582348978,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439502,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584175518,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584863847,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226425,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588341851,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849658,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582733129,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:78",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32",
        "fs/quota/compat.c:__do_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585556593,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:78",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079431,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:78",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201170,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:78",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589189859,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:62",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_ifreq_ioctl",
        "net/socket.c:compat_ifreq_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589092053,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:62",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int raw_copy_in_user(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287580768,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ]
    },
    {
      "addr": 13835058055290267320,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command"
      ],
      "caller_func": [
        "block/compat_ioctl.c:compat_cdrom_generic_command"
      ]
    },
    {
      "addr": 13835058055291233812,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293630844,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295247868,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl"
      ]
    },
    {
      "addr": 13835058055295979596,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:311",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287577744,
      "name": "raw_copy_in_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055290262704,
      "name": "raw_copy_in_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055295236144,
      "name": "raw_copy_in_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 13835058055295976224,
      "name": "raw_copy_in_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317714,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408238,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584144254,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815031,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586932505,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587948635,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588456042,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255474,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345934,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584079790,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584745799,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586873657,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587661739,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588168730,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308194,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398718,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584128014,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816455,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180985,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588280411,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588788218,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "raw_copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582387426,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate",
        "fs/compat_ioctl.c:compat_ioctl_preallocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478254,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "fs/quota/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__x32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32",
        "fs/quota/compat.c:__ia32_compat_sys_quotactl32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584232062,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584921527,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288121,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588415563,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl",
        "net/socket.c:ethtool_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928842,
      "name": "raw_copy_in_user",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess_64.h:182",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long unsigned int raw_copy_in_user(void * to, const void * from, long unsigned int n)
```
</details>
</li>
</ul>
