# Function: <code>vfs_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073642,
      "name": "vfs_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:35",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581235241,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:36",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234864,
      "name": "vfs_ioctl",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581313129,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:36",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312752,
      "name": "vfs_ioctl",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364844,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:38",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364464,
      "name": "vfs_ioctl",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581506300,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:39",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505920,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581662860,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:39",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662480,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581749196,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:39",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747456,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581867386,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:39",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864768,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581939786,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937120,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582171650,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:41",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167152,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582217766,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:41",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213680,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582243926,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238672,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582561750,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557392,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583090964,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086032,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583658900,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653680,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583876068,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870832,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584083108,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:44",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077856,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493427824,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493422256,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227007860,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:file_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227003996,
      "name": "vfs_ioctl",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286985792,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286981136,
      "name": "vfs_ioctl",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273128060,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273126596,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908522,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905856,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846106,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843440,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899834,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897168,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "vfs_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581969464,
      "name": "vfs_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:40",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/ioctl.c:do_vfs_ioctl"
      ],
      "caller_func": [
        "fs/compat_ioctl.c:do_ioctl_trans",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966800,
      "name": "vfs_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long int vfs_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```
</details>
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
