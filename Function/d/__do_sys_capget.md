# Function: <code>__do_sys_capget</code>

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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472780,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:150",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579506444,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:150",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525468,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551548,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583440,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583440,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563424,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563424,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568960,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568960,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642048,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642048,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737504,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737504,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868496,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868496,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918432,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:141",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918432,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
```

```json
{
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957680,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:141",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957680,
      "name": "__do_sys_capget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490704708,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__arm64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224768432,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283529088,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271430020,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579527852,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579456652,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525132,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
  "name": "__do_sys_capget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558092,
      "name": "__do_sys_capget",
      "external": false,
      "loc": "kernel/capability.c:148",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capget",
        "kernel/capability.c:__x64_sys_capget"
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
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr)
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
