# Function: <code>vfs_fallocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980608,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:231",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "fs/open.c:SyS_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980608,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135728,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:231",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "fs/open.c:SyS_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135728,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210816,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:242",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "fs/open.c:SyS_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210816,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256736,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:243",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "fs/open.c:SyS_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256736,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395856,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:243",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "fs/open.c:SyS_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395856,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 607
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550464,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:243",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550464,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636432,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:232",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636432,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753040,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753040,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825248,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825248,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046976,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:230",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_remove",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046976,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096880,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:230",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_remove",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096880,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121680,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:231",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121680,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438512,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:228",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438512,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957568,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:243",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "io_uring/io_uring.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957568,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583515856,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:243",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583515856,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 866
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731344,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:244",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731344,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 907
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932144,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:244",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate",
        "fs/ioctl.c:compat_ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "io_uring/sync.c:io_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932144,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 884
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493288704,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__arm64_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493288704,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226892728,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226892728,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286825184,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286825184,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273035834,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273035834,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793984,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793984,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731648,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731648,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785296,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785296,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int vfs_fallocate(struct file * file, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "vfs_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854432,
      "name": "vfs_fallocate",
      "external": true,
      "loc": "fs/open.c:233",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "fs/open.c:ksys_fallocate",
        "fs/ioctl.c:ioctl_preallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854432,
      "name": "vfs_fallocate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
