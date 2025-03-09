# Function: <code>__do_sys_memfd_create</code>

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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581547741,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:266",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581632925,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:247",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749501,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:248",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581821581,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038784,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038784,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582087552,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087552,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112624,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112624,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428944,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:266",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428944,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945056,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:266",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945056,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583501984,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:266",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583501984,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:294",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718672,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
    },
    {
      "addr": 18446744071596572575,
      "name": "__do_sys_memfd_create.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
```

```json
{
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919264,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:294",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919264,
      "name": "__do_sys_memfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493285740,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__arm64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226890088,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__se_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286820180,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__se_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273033640,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__se_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581790317,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581727997,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581781629,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
  "name": "__do_sys_memfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581850653,
      "name": "__do_sys_memfd_create",
      "external": false,
      "loc": "mm/memfd.c:250",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create"
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
long int __do_sys_memfd_create(const char * uname, unsigned int flags)
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
