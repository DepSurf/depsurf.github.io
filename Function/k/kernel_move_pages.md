# Function: <code>kernel_move_pages</code>

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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407184,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1725",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407184,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2276
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490672,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1758",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490672,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2270
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581600352,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1753",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581600352,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671024,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671024,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889376,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1793",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889376,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581935792,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1961",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935792,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961312,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1944",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961312,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266144,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:2012",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266144,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735184,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1950",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735184,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259760,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:2066",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259760,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583480128,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:2400",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480128,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672592,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:2426",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672592,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493114824,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__arm64_compat_sys_move_pages",
        "mm/migrate.c:__arm64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493114824,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286591264,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__se_compat_sys_move_pages",
        "mm/migrate.c:__se_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286591264,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639760,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639760,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580720,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580720,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631072,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631072,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
```

```json
{
  "name": "kernel_move_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697376,
      "name": "kernel_move_pages",
      "external": false,
      "loc": "mm/migrate.c:1786",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:__x32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_compat_sys_move_pages",
        "mm/migrate.c:__ia32_sys_move_pages",
        "mm/migrate.c:__x64_sys_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697376,
      "name": "kernel_move_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void * * pages, const int * nodes, int * status, int flags)
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
