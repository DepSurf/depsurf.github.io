# Function: <code>memfd_file_seals_ptr</code>

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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547600,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:137",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547600,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632784,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:118",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632784,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749360,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:118",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749360,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821440,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821440,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582038672,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038672,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582088032,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582113104,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582429424,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:136",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582945434,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:136",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583502358,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:136",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583719413,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:137",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583919894,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:137",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493284184,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__arm64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493284184,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226890488,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__se_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286819936,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__se_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286819936,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273031974,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__se_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273031974,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790176,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790176,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727856,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727856,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781488,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781488,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
```

```json
{
  "name": "memfd_file_seals_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850512,
      "name": "memfd_file_seals_ptr",
      "external": false,
      "loc": "mm/memfd.c:120",
      "file": "mm/memfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memfd.c:__ia32_sys_memfd_create",
        "mm/memfd.c:__x64_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850512,
      "name": "memfd_file_seals_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
unsigned int * memfd_file_seals_ptr(struct file * file)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
unsigned int * memfd_file_seals_ptr(struct file * file)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int * memfd_file_seals_ptr(struct file * file)
```
</details>
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
