# Function: <code>__do_compat_sys_keyctl</code>

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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582954793,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:59",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583064138,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:59",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583248753,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583354593,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690032,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:50",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690032,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583811424,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811424,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835680,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835680,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584198672,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x64_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198672,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800688,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800688,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498816,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498816,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730368,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730368,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
```

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977616,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:17",
      "file": "security/keys/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977616,
      "name": "__do_compat_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495099564,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__arm64_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289002196,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__se_compat_sys_keyctl"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583323329,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583260433,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583307105,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
  "name": "__do_compat_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583402097,
      "name": "__do_compat_sys_keyctl",
      "external": false,
      "loc": "security/keys/compat.c:55",
      "file": "security/keys/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
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
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5)
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
