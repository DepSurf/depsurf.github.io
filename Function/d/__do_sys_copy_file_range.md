# Function: <code>__do_sys_copy_file_range</code>

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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581574501,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1653",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581660229,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1653",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581778077,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581850301,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582075504,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1800",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075504,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125024,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1538",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125024,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149856,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1543",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149856,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466720,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1534",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466720,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986784,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1559",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986784,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547184,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1559",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547184,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763248,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1558",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763248,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965936,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1575",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965936,
      "name": "__do_sys_copy_file_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493316584,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__arm64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226918240,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__se_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286857336,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__se_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273055340,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__se_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581819037,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581756701,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581810349,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
  "name": "__do_sys_copy_file_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581879565,
      "name": "__do_sys_copy_file_range",
      "external": false,
      "loc": "fs/read_write.c:1716",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_copy_file_range",
        "fs/read_write.c:__x64_sys_copy_file_range"
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
long int __do_sys_copy_file_range(int fd_in, loff_t * off_in, int fd_out, loff_t * off_out, size_t len, unsigned int flags)
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
