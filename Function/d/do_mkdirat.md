# Function: <code>do_mkdirat</code>

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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652256,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3834",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652256,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738528,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3823",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738528,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855168,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3822",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855168,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927632,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927632,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157504,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3648",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157504,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582198672,
      "name": "do_mkdirat",
      "external": false,
      "loc": "fs/namei.c:3650",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198672,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223344,
      "name": "do_mkdirat",
      "external": false,
      "loc": "fs/namei.c:3820",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223344,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int do_mkdirat(int dfd, struct filename * name, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544784,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3892",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544784,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int do_mkdirat(int dfd, struct filename * name, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072656,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3986",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "io_uring/io_uring.c:io_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072656,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int do_mkdirat(int dfd, struct filename * name, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639184,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:4043",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "io_uring/fs.c:io_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639184,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int do_mkdirat(int dfd, struct filename * name, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856352,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:4124",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "io_uring/fs.c:io_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856352,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int do_mkdirat(int dfd, struct filename * name, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584063328,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:4133",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat",
        "io_uring/fs.c:io_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063328,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493408392,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__arm64_sys_mkdir",
        "fs/namei.c:__arm64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493408392,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226994060,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mkdir",
        "fs/namei.c:__se_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226994060,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286967200,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mkdir",
        "fs/namei.c:__se_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286967200,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273119238,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__se_sys_mkdir",
        "fs/namei.c:__se_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273119238,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896368,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896368,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833968,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833968,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887680,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887680,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
```

```json
{
  "name": "do_mkdirat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957184,
      "name": "do_mkdirat",
      "external": true,
      "loc": "fs/namei.c:3817",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/namei.c:__ia32_sys_mkdir",
        "fs/namei.c:__x64_sys_mkdir",
        "fs/namei.c:__ia32_sys_mkdirat",
        "fs/namei.c:__x64_sys_mkdirat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957184,
      "name": "do_mkdirat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
long int do_mkdirat(int dfd, const char * pathname, umode_t mode)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct filename * name</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * pathname</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
