# Function: <code>__do_sys_timerfd_create</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581915484,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582000716,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582136312,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582213464,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450032,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:390",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450032,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582506720,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:390",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582506720,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534496,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:390",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534496,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850528,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:406",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850528,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414048,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:406",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414048,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001376,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:406",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001376,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226048,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:406",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226048,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
long int __do_sys_timerfd_create(int clockid, int flags)
```

```json
{
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440640,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:406",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440640,
      "name": "__do_sys_timerfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__arm64_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227296000,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__se_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287391316,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__se_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273374268,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__se_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582182200,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582119800,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582172680,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
  "name": "__do_sys_timerfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582249032,
      "name": "__do_sys_timerfd_create",
      "external": false,
      "loc": "fs/timerfd.c:387",
      "file": "fs/timerfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__ia32_sys_timerfd_create",
        "fs/timerfd.c:__x64_sys_timerfd_create"
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
long int __do_sys_timerfd_create(int clockid, int flags)
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
