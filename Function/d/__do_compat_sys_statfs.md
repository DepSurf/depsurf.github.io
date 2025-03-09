# Function: <code>__do_compat_sys_statfs</code>

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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815344,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:286",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815344,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902336,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:286",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902336,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027888,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027888,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105824,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105824,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342640,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342640,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394160,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:302",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394160,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421456,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421456,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744272,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x64_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744272,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291152,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291152,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875008,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875008,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096768,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096768,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312912,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:305",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312912,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493644408,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__arm64_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493644408,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287235792,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287235792,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074560,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074560,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012112,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012112,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065840,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065840,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
```

```json
{
  "name": "__do_compat_sys_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137584,
      "name": "__do_compat_sys_statfs",
      "external": false,
      "loc": "fs/statfs.c:300",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs",
        "fs/statfs.c:__ia32_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137584,
      "name": "__do_compat_sys_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
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
long int __do_compat_sys_statfs(const char * pathname, struct compat_statfs * buf)
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
