# Function: <code>do_compat_fcntl64</code>

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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658656,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658656,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744912,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744912,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862160,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862160,
      "name": "do_compat_fcntl64",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934528,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934528,
      "name": "do_compat_fcntl64",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164448,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164448,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210896,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210896,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235872,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:618",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235872,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554464,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:622",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x64_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x64_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554464,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583082960,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:600",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082960,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650368,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:601",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650368,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867536,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:602",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867536,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074592,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:603",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074592,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493417888,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__arm64_compat_sys_fcntl",
        "fs/fcntl.c:__arm64_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493417888,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286977344,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_compat_sys_fcntl",
        "fs/fcntl.c:__se_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286977344,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903264,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903264,
      "name": "do_compat_fcntl64",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840864,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840864,
      "name": "do_compat_fcntl64",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894576,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894576,
      "name": "do_compat_fcntl64",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "do_compat_fcntl64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964160,
      "name": "do_compat_fcntl64",
      "external": false,
      "loc": "fs/fcntl.c:613",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__x32_compat_sys_fcntl",
        "fs/fcntl.c:__ia32_compat_sys_fcntl",
        "fs/fcntl.c:__x32_compat_sys_fcntl64",
        "fs/fcntl.c:__ia32_compat_sys_fcntl64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964160,
      "name": "do_compat_fcntl64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_compat_fcntl64(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```
</details>
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
