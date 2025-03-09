# Function: <code>__do_sys_vmsplice</code>

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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799440,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1345",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799440,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886576,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886576,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012656,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1355",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012656,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090624,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090624,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323872,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1351",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323872,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375312,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1291",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375312,
      "name": "__do_sys_vmsplice",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403584,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1296",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403584,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1298",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724304,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    },
    {
      "addr": 18446744071592231279,
      "name": "__do_sys_vmsplice.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1294",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269280,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
    },
    {
      "addr": 18446744071594011264,
      "name": "__do_sys_vmsplice.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852096,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1294",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852096,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071760,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1535",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071760,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288304,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1598",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288304,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493622904,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__arm64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493622904,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227163760,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227163760,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287216832,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287216832,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273265976,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273265976,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059360,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059360,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581996912,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996912,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582050640,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050640,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122320,
      "name": "__do_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1363",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_vmsplice",
        "fs/splice.c:__x64_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122320,
      "name": "__do_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
long int __do_sys_vmsplice(int fd, const struct iovec * uiov, long unsigned int nr_segs, unsigned int flags)
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
