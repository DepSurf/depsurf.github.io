# Function: <code>vfs_lstat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_lstat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_lstat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013600,
      "name": "vfs_lstat",
      "external": true,
      "loc": "fs/stat.c:127",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_newlstat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64",
        "fs/compat.c:C_SYSC_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013600,
      "name": "vfs_lstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int vfs_lstat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_lstat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581173281,
      "name": "vfs_lstat",
      "external": true,
      "loc": "fs/stat.c:127",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_lstat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64",
        "fs/compat.c:C_SYSC_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171984,
      "name": "vfs_lstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int vfs_lstat(const char * name, struct kstat * stat)
```

```json
{
  "name": "vfs_lstat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250273,
      "name": "vfs_lstat",
      "external": true,
      "loc": "fs/stat.c:127",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_lstat"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64",
        "fs/compat.c:C_SYSC_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248976,
      "name": "vfs_lstat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596274471,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3033",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350614,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3033",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299681,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3033",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newlstat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602590503,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3099",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376982,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3099",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439537,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3099",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newlstat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602759143,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3120",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390168,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3120",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598168,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3120",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604553258,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3195",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418184,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3195",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684152,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3195",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604647545,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3206",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434057,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3206",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802329,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3206",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604659806,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436969,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874921,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609013098,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3329",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084137,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3329",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100729,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3329",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579086227,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3129",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582147289,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3129",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579092835,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3382",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172137,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3382",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579116131,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3364",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489433,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3364",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579148155,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3142",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012283,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3142",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579193739,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3296",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583575419,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3296",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198363,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:2911",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791515,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:2911",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227627,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3192",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996973,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3192",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510810336,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493346532,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_newlstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243256140,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 3226939544,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_newlstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302373892,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286892988,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_newlstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270607436,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273074276,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_newlstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604586078,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432809,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843657,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604577755,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361913,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781321,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663902,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432729,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834969,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
  "name": "vfs_lstat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663907,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:clean_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441913,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904361,
      "name": "vfs_lstat",
      "external": false,
      "loc": "include/linux/fs.h:3268",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_lstat"
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
int vfs_lstat(const char * name, struct kstat * stat)
```
</details>
</li>
</ul>
