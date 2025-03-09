# Function: <code>do_compat_signalfd4</code>

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
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914416,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:334",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914416,
      "name": "do_compat_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997968,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:334",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997968,
      "name": "do_compat_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134544,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134544,
      "name": "do_compat_signalfd4",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211696,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211696,
      "name": "do_compat_signalfd4",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582448821,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:337",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582505493,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:337",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582533270,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:336",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582849334,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:326",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__x64_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x64_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583411891,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:327",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583999107,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:327",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584223779,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:327",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584438371,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:327",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493774924,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__arm64_compat_sys_signalfd",
        "fs/signalfd.c:__arm64_compat_sys_signalfd4"
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
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287388388,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/signalfd.c:__se_compat_sys_signalfd",
        "fs/signalfd.c:__se_compat_sys_signalfd4"
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
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180432,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180432,
      "name": "do_compat_signalfd4",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118064,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118064,
      "name": "do_compat_signalfd4",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170912,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170912,
      "name": "do_compat_signalfd4",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```

```json
{
  "name": "do_compat_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247872,
      "name": "do_compat_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:335",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247872,
      "name": "do_compat_signalfd4",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
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
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_compat_signalfd4(int ufd, const compat_sigset_t * user_mask, compat_size_t sigsetsize, int flags)
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
