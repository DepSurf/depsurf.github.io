# Function: <code>vfs_fstat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013280,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:77",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64",
        "fs/stat.c:SYSC_fstat",
        "fs/stat.c:SYSC_newfstat",
        "fs/compat.c:C_SYSC_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013280,
      "name": "vfs_fstat",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171664,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:77",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat",
        "fs/compat.c:C_SYSC_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171664,
      "name": "vfs_fstat",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int vfs_fstat(unsigned int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248656,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:77",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat",
        "fs/compat.c:C_SYSC_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248656,
      "name": "vfs_fstat",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579350742,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3044",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299905,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3044",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newfstat",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579377110,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3110",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439761,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3110",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newfstat",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579390524,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3131",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598508,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3131",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579418540,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3206",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684492,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3206",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434413,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3217",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802685,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3217",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579437325,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875277,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579084477,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3340",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101725,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3340",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148112,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:138",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148112,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172960,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:156",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172960,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490256,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:174",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490256,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010320,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:174",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010320,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573056,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:178",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573056,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583789136,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:184",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789136,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int vfs_fstat(int fd, struct kstat * stat)
```

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994832,
      "name": "vfs_fstat",
      "external": true,
      "loc": "fs/stat.c:190",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:vfs_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994832,
      "name": "vfs_fstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493346848,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226939660,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286893156,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273074408,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_newfstat"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433165,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844013,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579362269,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781677,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433085,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835325,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
  "name": "vfs_fstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579442269,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904717,
      "name": "vfs_fstat",
      "external": false,
      "loc": "include/linux/fs.h:3279",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
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
int vfs_fstat(unsigned int fd, struct kstat * stat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int vfs_fstat(int fd, struct kstat * stat)
```
</details>
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
