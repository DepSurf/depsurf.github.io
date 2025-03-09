# Function: <code>vfs_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_stat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013568,
      "name": "vfs_stat",
      "external": true,
      "loc": "fs/stat.c:121",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_stat",
        "fs/stat.c:SYSC_newstat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_stat64",
        "fs/compat.c:C_SYSC_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013568,
      "name": "vfs_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int vfs_stat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581173185,
      "name": "vfs_stat",
      "external": true,
      "loc": "fs/stat.c:121",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_stat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_stat64",
        "fs/compat.c:C_SYSC_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171952,
      "name": "vfs_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int vfs_stat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250177,
      "name": "vfs_stat",
      "external": true,
      "loc": "fs/stat.c:121",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_stat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_stat64",
        "fs/compat.c:C_SYSC_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248944,
      "name": "vfs_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855396,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3028",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350486,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3028",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299569,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3028",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855444,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3094",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376854,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3094",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439425,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3094",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857337,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3115",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389976,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3115",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597992,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3115",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857478,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3190",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417992,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3190",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683976,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3190",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857780,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3201",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433865,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3201",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802137,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3201",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857764,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436777,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874729,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862353,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3324",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083961,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3324",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100553,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3324",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579086048,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3125",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582146761,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3125",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579092656,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3378",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171609,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3378",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579115952,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3360",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488905,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3360",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147979,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3138",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011691,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3138",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579193531,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3292",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583574699,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3292",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198155,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:2907",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790795,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:2907",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227419,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3188",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583997232,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3188",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490178420,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493346372,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newstat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224387396,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 3226939416,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newstat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282234376,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286892812,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newstat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271338254,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273074210,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_newstat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857764,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432617,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843465,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578850820,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361721,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781129,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857764,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432537,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834777,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
  "name": "vfs_stat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857844,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "init/do_mounts_md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts_md.c:bstat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441721,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904169,
      "name": "vfs_stat",
      "external": false,
      "loc": "include/linux/fs.h:3263",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_stat"
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
int vfs_stat(const char * name, struct kstat * stat)
```
</details>
</li>
</ul>
