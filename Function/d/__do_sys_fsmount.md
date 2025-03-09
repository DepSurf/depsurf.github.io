# Function: <code>__do_sys_fsmount</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581937782,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3350",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582010422,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3434",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246880,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071582257305,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3456",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296128,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071591339986,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3516",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322880,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    },
    {
      "addr": 18446744071591282695,
      "name": "__do_sys_fsmount.cold",
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
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3593",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643328,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071592230840,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181136,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
    },
    {
      "addr": 18446744071594010808,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3742",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756256,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 799
    },
    {
      "addr": 18446744071596051641,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3929",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973184,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
    },
    {
      "addr": 18446744071596574171,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```

```json
{
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3943",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185456,
      "name": "__do_sys_fsmount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
    },
    {
      "addr": 18446744071597478709,
      "name": "__do_sys_fsmount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493532332,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227090876,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287100372,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273205042,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581979158,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581916726,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581970438,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
  "name": "__do_sys_fsmount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582041686,
      "name": "__do_sys_fsmount",
      "external": false,
      "loc": "fs/namespace.c:3381",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_fsmount(int fs_fd, unsigned int flags, unsigned int attr_flags)
```
</details>
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
