# Function: <code>__sys_setgid</code>

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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527552,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527552,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563664,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563664,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586576,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586576,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612672,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612672,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643776,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:417",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643776,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624336,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:418",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624336,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630800,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:423",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630800,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707200,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:423",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707200,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809824,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:430",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809824,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945552,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:431",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945552,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995152,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:438",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995152,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034560,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:438",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034560,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490778704,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_setgid",
        "kernel/uid16.c:__arm64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490778704,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224813684,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setgid",
        "kernel/uid16.c:__se_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224813684,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283603536,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283603536,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271462466,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_setgid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271462466,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588976,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588976,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517616,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517616,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586256,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586256,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
```

```json
{
  "name": "__sys_setgid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619904,
      "name": "__sys_setgid",
      "external": true,
      "loc": "kernel/sys.c:412",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_setgid",
        "kernel/sys.c:__x64_sys_setgid",
        "kernel/uid16.c:__ia32_sys_setgid16",
        "kernel/uid16.c:__x64_sys_setgid16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619904,
      "name": "__sys_setgid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long int __sys_setgid(gid_t gid)
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
