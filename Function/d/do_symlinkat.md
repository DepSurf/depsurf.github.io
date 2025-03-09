# Function: <code>do_symlinkat</code>

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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654240,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4144",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654240,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740528,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4133",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740528,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857088,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4134",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857088,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929552,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929552,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159632,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:3960",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159632,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200128,
      "name": "do_symlinkat",
      "external": false,
      "loc": "fs/namei.c:3960",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200128,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224848,
      "name": "do_symlinkat",
      "external": false,
      "loc": "fs/namei.c:4179",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224848,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int do_symlinkat(struct filename * from, int newdfd, struct filename * to)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547200,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4257",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547200,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int do_symlinkat(struct filename * from, int newdfd, struct filename * to)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075312,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4352",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "io_uring/io_uring.c:io_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075312,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int do_symlinkat(struct filename * from, int newdfd, struct filename * to)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642096,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4408",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "io_uring/fs.c:io_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642096,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int do_symlinkat(struct filename * from, int newdfd, struct filename * to)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859264,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4484",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "io_uring/fs.c:io_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859264,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int do_symlinkat(struct filename * from, int newdfd, struct filename * to)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584066272,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4491",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat",
        "io_uring/fs.c:io_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066272,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493410168,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__arm64_sys_symlink",
        "fs/namei.c:__arm64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493410168,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226995748,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__se_sys_symlink",
        "fs/namei.c:__se_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226995748,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286969568,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__se_sys_symlink",
        "fs/namei.c:__se_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286969568,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273120834,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__se_sys_symlink",
        "fs/namei.c:__se_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273120834,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898288,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898288,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835888,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835888,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889600,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889600,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
```

```json
{
  "name": "do_symlinkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959104,
      "name": "do_symlinkat",
      "external": true,
      "loc": "fs/namei.c:4129",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_symlink",
        "fs/namei.c:__ia32_sys_symlink",
        "fs/namei.c:__x64_sys_symlink",
        "fs/namei.c:__ia32_sys_symlinkat",
        "fs/namei.c:__x64_sys_symlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959104,
      "name": "do_symlinkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long int do_symlinkat(const char * oldname, int newdfd, const char * newname)
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
<code>struct filename * from</code>
</li>
<li>
<b>Param added. </b>
<code>struct filename * to</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * oldname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * newname</code>
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
