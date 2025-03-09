# Function: <code>__do_compat_sys_migrate_pages</code>

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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311920,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1579",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311920,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393472,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1619",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393472,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505648,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1665",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505648,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570016,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570016,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783472,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1736",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783472,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834816,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1712",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834816,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865648,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1726",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865648,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493006616,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_migrate_pages"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286435188,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__se_compat_sys_migrate_pages"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538752,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538752,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480512,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480512,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530064,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530064,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```

```json
{
  "name": "__do_compat_sys_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596768,
      "name": "__do_compat_sys_migrate_pages",
      "external": false,
      "loc": "mm/mempolicy.c:1667",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_migrate_pages",
        "mm/mempolicy.c:__ia32_compat_sys_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596768,
      "name": "__do_compat_sys_migrate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_migrate_pages(compat_pid_t pid, compat_ulong_t maxnode, const compat_ulong_t * old_nodes, const compat_ulong_t * new_nodes)
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
