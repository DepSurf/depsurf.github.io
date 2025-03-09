# Function: <code>ksys_dup3</code>

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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712272,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:874",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712272,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798784,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:904",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798784,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917584,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917584,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989968,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989968,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223760,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:935",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223760,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271904,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1127",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271904,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297808,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1138",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297808,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616880,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1204",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616880,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151520,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1206",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151520,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725200,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1216",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725200,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942256,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1231",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942256,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147616,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:1355",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147616,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493504408,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__arm64_sys_dup2",
        "fs/file.c:__arm64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493504408,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227061136,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__se_sys_dup2",
        "fs/file.c:__se_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227061136,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287066080,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__se_sys_dup2",
        "fs/file.c:__se_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287066080,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273176656,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__se_sys_dup2",
        "fs/file.c:__se_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273176656,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958704,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958704,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896272,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896272,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950016,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950016,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
```

```json
{
  "name": "ksys_dup3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019920,
      "name": "ksys_dup3",
      "external": false,
      "loc": "fs/file.c:910",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__ia32_sys_dup2",
        "fs/file.c:__x64_sys_dup2",
        "fs/file.c:__ia32_sys_dup3",
        "fs/file.c:__x64_sys_dup3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019920,
      "name": "ksys_dup3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int ksys_dup3(unsigned int oldfd, unsigned int newfd, int flags)
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
