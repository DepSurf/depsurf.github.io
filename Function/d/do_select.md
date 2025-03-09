# Function: <code>do_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits * fds, struct timespec * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077536,
      "name": "do_select",
      "external": true,
      "loc": "fs/select.c:399",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077536,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2060
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
int do_select(int n, fd_set_bits * fds, struct timespec * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240480,
      "name": "do_select",
      "external": true,
      "loc": "fs/select.c:403",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240480,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2050
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
int do_select(int n, fd_set_bits * fds, struct timespec * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318352,
      "name": "do_select",
      "external": true,
      "loc": "fs/select.c:404",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318352,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2008
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
int do_select(int n, fd_set_bits * fds, struct timespec * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371376,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:451",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371376,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2016
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
int do_select(int n, fd_set_bits * fds, struct timespec * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512880,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:450",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512880,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1998
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670608,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:449",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670608,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1907
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756912,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:474",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756912,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1893
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874544,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874544,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946800,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946800,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177648,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177648,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2049
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224848,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224848,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2083
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250896,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250896,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2037
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568736,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:478",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568736,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2112
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098000,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:479",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098000,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666208,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:479",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666208,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2114
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583883440,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:479",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883440,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2184
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090608,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:479",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090608,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2184
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493442808,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493442808,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227013464,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227013464,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286997184,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286997184,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2136
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273132250,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273132250,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1356
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915536,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915536,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853120,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853120,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906848,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906848,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1901
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
int do_select(int n, fd_set_bits * fds, struct timespec64 * end_time)
```

```json
{
  "name": "do_select",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976464,
      "name": "do_select",
      "external": false,
      "loc": "fs/select.c:476",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976464,
      "name": "do_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * end_time</code> ➡️ <code>struct timespec64 * end_time</code>
</li>
</ul>
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
