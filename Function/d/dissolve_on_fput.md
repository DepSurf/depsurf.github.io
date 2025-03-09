# Function: <code>dissolve_on_fput</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936320,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1839",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936320,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008960,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008960,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245472,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1897",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245472,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294720,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1903",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294720,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321840,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1918",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321840,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642288,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1919",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:__do_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642288,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179600,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1960",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179600,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754656,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:2065",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754656,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971584,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:2052",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971584,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183888,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:2054",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183888,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493531104,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:__arm64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493531104,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227083060,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227083060,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287098784,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287098784,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273197352,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273197352,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977696,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977696,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915264,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915264,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968976,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968976,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void dissolve_on_fput(struct vfsmount * mnt)
```

```json
{
  "name": "dissolve_on_fput",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039424,
      "name": "dissolve_on_fput",
      "external": true,
      "loc": "fs/namespace.c:1842",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:__fput",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039424,
      "name": "dissolve_on_fput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void dissolve_on_fput(struct vfsmount * mnt)
```
</details>
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
