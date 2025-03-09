# Function: <code>do_fsync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206112,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:213",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_fsync",
        "fs/sync.c:SyS_fdatasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206112,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370784,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:213",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_fdatasync",
        "fs/sync.c:SyS_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370784,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448640,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:214",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_fdatasync",
        "fs/sync.c:SyS_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448640,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502800,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:214",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_fdatasync",
        "fs/sync.c:SyS_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502800,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644944,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:215",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_fdatasync",
        "fs/sync.c:SyS_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644944,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803728,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803728,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890736,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890736,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015840,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015840,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093792,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093792,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582330805,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:219",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582382229,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:219",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582409989,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:218",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582731381,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:219",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583277621,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:206",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583860277,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:206",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584082021,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:206",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584298085,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:206",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493629920,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__arm64_sys_fdatasync",
        "fs/sync.c:__arm64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493629920,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227170148,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__se_sys_fdatasync",
        "fs/sync.c:__se_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227170148,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287220240,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__se_sys_fdatasync",
        "fs/sync.c:__se_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287220240,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273269970,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__se_sys_fdatasync",
        "fs/sync.c:__se_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273269970,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062528,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062528,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000080,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000080,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053808,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053808,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int do_fsync(unsigned int fd, int datasync)
```

```json
{
  "name": "do_fsync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125488,
      "name": "do_fsync",
      "external": false,
      "loc": "fs/sync.c:216",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_fdatasync",
        "fs/sync.c:__x64_sys_fdatasync",
        "fs/sync.c:__ia32_sys_fsync",
        "fs/sync.c:__x64_sys_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125488,
      "name": "do_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int do_fsync(unsigned int fd, int datasync)
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
