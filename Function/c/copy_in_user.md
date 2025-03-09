# Function: <code>copy_in_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_in_user(void * to, const void * from, unsigned int len)
```

```json
{
  "name": "copy_in_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005168,
      "name": "copy_in_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:57",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005168,
      "name": "copy_in_user",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_in_user(void * to, const void * from, unsigned int len)
```

```json
{
  "name": "copy_in_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295648,
      "name": "copy_in_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:57",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295648,
      "name": "copy_in_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
long unsigned int copy_in_user(void * to, const void * from, unsigned int len)
```

```json
{
  "name": "copy_in_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414512,
      "name": "copy_in_user",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:57",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "fs/quota/compat.c:sys32_quotactl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "block/compat_ioctl.c:compat_blkdev_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt",
        "net/compat.c:compat_mc_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414512,
      "name": "copy_in_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581680350,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
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
      "addr": 18446744071581751827,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
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
      "addr": 18446744071583385584,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
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
      "addr": 18446744071583996951,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585923787,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586905454,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
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
      "addr": 18446744071587210152,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:159",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581825545,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071581898947,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071583564931,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071584212861,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586364667,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397355,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071587724537,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998016,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071582083064,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071583780845,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071584432926,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623813,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695614,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
      "addr": 18446744071588059364,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:160",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582086537,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582177192,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071583860909,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584529785,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586772693,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587831156,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588235191,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582250071,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582340328,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584051379,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584727105,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027146,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588134092,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588627155,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582348920,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582439464,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584175472,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584863809,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226392,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588341798,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588849639,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582733091,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071585556552,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079401,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201121,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589189819,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:205",
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
  "name": "copy_in_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589092004,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:205",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493946728,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:sg_grt_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496036192,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497256912,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500321224,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501850096,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446603336502428304,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287584264,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans",
        "fs/compat_ioctl.c:sg_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290266936,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "block/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_driver_ioctl",
        "block/compat_ioctl.c:compat_cdrom_generic_command",
        "block/compat_ioctl.c:compat_cdrom_generic_command"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291233720,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap",
        "drivers/video/fbdev/core/fbmem.c:fb_getput_cmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293627952,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295251076,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 13835058055295979568,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317656,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582408200,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584144208,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584814993,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586932472,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587948582,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588456023,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255416,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582345896,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584079744,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584745761,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586873624,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587661686,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588168711,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308136,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582398680,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584127968,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584816417,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180952,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588280358,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588788199,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
  "name": "copy_in_user",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582387368,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071582478216,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584232016,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071584921489,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl",
        "drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288088,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588415510,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
      "addr": 18446744071588928823,
      "name": "copy_in_user",
      "external": false,
      "loc": "include/linux/uaccess.h:157",
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long unsigned int copy_in_user(void * to, const void * from, unsigned int len)
```
</details>
</li>
</ul>
