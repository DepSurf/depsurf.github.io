# Function: <code>__do_sys_pkey_alloc</code>

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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581177156,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:591",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258100,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:592",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332628,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:593",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581392036,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:623",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581589524,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:649",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635456,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:662",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635456,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657104,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:663",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657104,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:673",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925296,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071592200522,
      "name": "__do_sys_pkey_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:772",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332096,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071593977146,
      "name": "__do_sys_pkey_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:829",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582832576,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071596033018,
      "name": "__do_sys_pkey_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:850",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047968,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071596554968,
      "name": "__do_sys_pkey_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```

```json
{
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:841",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229776,
      "name": "__do_sys_pkey_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071597459073,
      "name": "__do_sys_pkey_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581360884,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:623",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581304644,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:623",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581352084,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:623",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
  "name": "__do_sys_pkey_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581416020,
      "name": "__do_sys_pkey_alloc",
      "external": false,
      "loc": "mm/mprotect.c:623",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:__ia32_sys_pkey_alloc",
        "mm/mprotect.c:__x64_sys_pkey_alloc"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long int __do_sys_pkey_alloc(long unsigned int flags, long unsigned int init_val)
```
</details>
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
