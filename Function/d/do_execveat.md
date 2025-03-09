# Function: <code>do_execveat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581025632,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1649",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:SyS_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025632,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581185451,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1798",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:SyS_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184752,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581262667,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1826",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:SyS_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262048,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581311732,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1858",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:SyS_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311136,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581451764,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1862",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:SyS_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451152,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581610552,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1897",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611072,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696728,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1897",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697424,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581812629,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815072,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581885205,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887664,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114688,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:2008",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114688,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582158407,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:1994",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582182644,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:1994",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582500087,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:1996",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583025287,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:2023",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583589271,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:2033",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583805191,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:2040",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
  "name": "do_execveat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011383,
      "name": "do_execveat",
      "external": false,
      "loc": "fs/exec.c:2061",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493360660,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__arm64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493363512,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226952816,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__se_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226952152,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286909632,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__se_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286910160,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273085470,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__se_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273084912,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581853941,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856400,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581793317,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794000,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581845253,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847712,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
```

```json
{
  "name": "do_execveat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914309,
      "name": "do_execveat",
      "external": true,
      "loc": "fs/exec.c:1900",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_execveat",
        "fs/exec.c:__x64_sys_execveat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917232,
      "name": "do_execveat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int do_execveat(int fd, struct filename * filename, const const char * * __argv, const const char * * __envp, int flags)
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
