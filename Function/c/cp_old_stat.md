# Function: <code>cp_old_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013632,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:140",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SYSC_stat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013632,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172016,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:140",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SYSC_fstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172016,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249008,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:140",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SYSC_fstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249008,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296832,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:206",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SYSC_fstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296832,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436688,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:207",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:SYSC_fstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436688,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:207",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594720,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071581599318,
      "name": "cp_old_stat.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:207",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680704,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071581685302,
      "name": "cp_old_stat.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798832,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581803494,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871424,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581876086,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:229",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097120,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071582102296,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:217",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143856,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071591339528,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:235",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168752,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071591282244,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:253",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486048,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071592229278,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:267",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007376,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
    },
    {
      "addr": 18446744071594008853,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569792,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:282",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569792,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785856,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:288",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785856,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583991472,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:316",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991472,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840160,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581844822,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777824,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581782486,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831472,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581836134,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```

```json
{
  "name": "cp_old_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cp_old_stat",
      "external": false,
      "loc": "fs/stat.c:209",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900864,
      "name": "cp_old_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071581905297,
      "name": "cp_old_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cp_old_stat(struct kstat * stat, struct __old_kernel_stat * statbuf)
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
