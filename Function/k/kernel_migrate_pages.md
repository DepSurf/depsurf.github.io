# Function: <code>kernel_migrate_pages</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310784,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1369",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310784,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392336,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1409",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392336,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504464,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1455",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504464,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568864,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568864,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782192,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1528",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782192,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833536,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1504",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833536,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864384,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1518",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864384,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155920,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1513",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155920,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611152,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1577",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611152,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134384,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1592",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134384,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344704,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1603",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344704,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583580752,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1589",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580752,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493005840,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages",
        "mm/mempolicy.c:__arm64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493005840,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286434288,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__se_compat_sys_migrate_pages",
        "mm/mempolicy.c:__se_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286434288,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537600,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537600,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479360,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479360,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528912,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528912,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```

```json
{
  "name": "kernel_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595600,
      "name": "kernel_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_sys_migrate_pages",
        "mm/mempolicy.c:__x64_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595600,
      "name": "kernel_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int * old_nodes, const long unsigned int * new_nodes)
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
