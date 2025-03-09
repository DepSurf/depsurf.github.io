# Function: <code>__do_sys_userfaultfd</code>

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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581923459,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1901",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582007811,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1919",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582143688,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1939",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220888,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
long int __do_sys_userfaultfd(int flags)
```

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457920,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2004",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457920,
      "name": "__do_sys_userfaultfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
long int __do_sys_userfaultfd(int flags)
```

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1964",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514816,
      "name": "__do_sys_userfaultfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071591341066,
      "name": "__do_sys_userfaultfd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
long int __do_sys_userfaultfd(int flags)
```

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2050",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542640,
      "name": "__do_sys_userfaultfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071591283767,
      "name": "__do_sys_userfaultfd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
long int __do_sys_userfaultfd(int flags)
```

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2062",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858800,
      "name": "__do_sys_userfaultfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071592236630,
      "name": "__do_sys_userfaultfd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
long int __do_sys_userfaultfd(int flags)
```

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2061",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422512,
      "name": "__do_sys_userfaultfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071594016845,
      "name": "__do_sys_userfaultfd.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584009840,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2150",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584235696,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2178",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584450112,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:2290",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493788488,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__arm64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227311172,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__se_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287400800,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__se_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273387280,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__se_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582189624,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582127144,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582180104,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
  "name": "__do_sys_userfaultfd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582256136,
      "name": "__do_sys_userfaultfd",
      "external": false,
      "loc": "fs/userfaultfd.c:1945",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__ia32_sys_userfaultfd",
        "fs/userfaultfd.c:__x64_sys_userfaultfd"
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
long int __do_sys_userfaultfd(int flags)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long int __do_sys_userfaultfd(int flags)
```
</details>
</li>
</ul>
