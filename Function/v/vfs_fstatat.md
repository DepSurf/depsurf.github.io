# Function: <code>vfs_fstatat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flag)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013376,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:90",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat",
        "fs/stat.c:SYSC_stat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_newfstatat",
        "fs/compat.c:C_SYSC_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013376,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flag)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171760,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:90",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat",
        "fs/stat.c:SYSC_newfstatat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat",
        "fs/compat.c:C_SYSC_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171760,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flag)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248752,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:90",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat",
        "fs/stat.c:SYSC_newfstatat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat",
        "fs/compat.c:C_SYSC_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248752,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579350854,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3038",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299793,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3038",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newfstatat",
        "fs/stat.c:SYSC_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579377222,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3104",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439649,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3104",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:C_SYSC_newfstatat",
        "fs/stat.c:SYSC_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579390352,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3125",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598336,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3125",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579418368,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3200",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684320,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3200",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434241,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3211",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802513,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3211",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579437153,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875105,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579084305,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3334",
      "file": "arch/x86/kernel/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100897,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3334",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582147633,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:204",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148720,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582172481,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:222",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173568,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582489777,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:240",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490864,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011088,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:247",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011088,
      "name": "vfs_fstatat",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573984,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:262",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573984,
      "name": "vfs_fstatat",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790080,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:268",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790080,
      "name": "vfs_fstatat",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
```

```json
{
  "name": "vfs_fstatat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996973,
      "name": "vfs_fstatat",
      "external": true,
      "loc": "fs/stat.c:279",
      "file": "fs/stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997504,
      "name": "vfs_fstatat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
  "name": "vfs_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493346688,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226939780,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_fstatat64"
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
  "name": "vfs_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286891448,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273074342,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579432993,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843841,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579362097,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781505,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579432913,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835153,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
  "name": "vfs_fstatat",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579442097,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "arch/x86/ia32/sys_ia32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581904545,
      "name": "vfs_fstatat",
      "external": false,
      "loc": "include/linux/fs.h:3273",
      "file": "fs/stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_sys_newfstatat"
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
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flag)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int vfs_fstatat(int dfd, const char * filename, struct kstat * stat, int flags)
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
