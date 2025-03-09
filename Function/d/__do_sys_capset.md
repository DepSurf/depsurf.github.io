# Function: <code>__do_sys_capset</code>

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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579473180,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:224",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579506844,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:224",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525868,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551948,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583904,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583904,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563904,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563904,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569424,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569424,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643088,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643088,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738304,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738304,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869344,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869344,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919040,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:220",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919040,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
```

```json
{
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958288,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:220",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958288,
      "name": "__do_sys_capset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490705676,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__arm64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224769032,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283529692,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271430388,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__se_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579528252,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579457052,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525532,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
  "name": "__do_sys_capset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558524,
      "name": "__do_sys_capset",
      "external": false,
      "loc": "kernel/capability.c:222",
      "file": "kernel/capability.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
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
long int __do_sys_capset(cap_user_header_t header, const cap_user_data_t data)
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
