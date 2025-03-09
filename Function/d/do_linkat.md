# Function: <code>do_linkat</code>

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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654624,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4275",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654624,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740912,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4264",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740912,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857456,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4265",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857456,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929920,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929920,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160064,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4091",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160064,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201664,
      "name": "do_linkat",
      "external": false,
      "loc": "fs/namei.c:4091",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201664,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226432,
      "name": "do_linkat",
      "external": false,
      "loc": "fs/namei.c:4324",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226432,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int do_linkat(int olddfd, struct filename * old, int newdfd, struct filename * new, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547824,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4402",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547824,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
int do_linkat(int olddfd, struct filename * old, int newdfd, struct filename * new, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076000,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4497",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "io_uring/io_uring.c:io_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076000,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int do_linkat(int olddfd, struct filename * old, int newdfd, struct filename * new, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642864,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4553",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "io_uring/fs.c:io_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642864,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
int do_linkat(int olddfd, struct filename * old, int newdfd, struct filename * new, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860032,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4625",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "io_uring/fs.c:io_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860032,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int do_linkat(int olddfd, struct filename * old, int newdfd, struct filename * new, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067040,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4632",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat",
        "io_uring/fs.c:io_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067040,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493410568,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__arm64_sys_link",
        "fs/namei.c:__arm64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493410568,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226996096,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__se_sys_link",
        "fs/namei.c:__se_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226996096,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286970096,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__se_sys_link",
        "fs/namei.c:__se_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286970096,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273121192,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__se_sys_link",
        "fs/namei.c:__se_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273121192,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898656,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898656,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836256,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836256,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889968,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889968,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
```

```json
{
  "name": "do_linkat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959472,
      "name": "do_linkat",
      "external": true,
      "loc": "fs/namei.c:4260",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:maybe_link",
        "fs/namei.c:__ia32_sys_link",
        "fs/namei.c:__x64_sys_link",
        "fs/namei.c:__ia32_sys_linkat",
        "fs/namei.c:__x64_sys_linkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959472,
      "name": "do_linkat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int do_linkat(int olddfd, const char * oldname, int newdfd, const char * newname, int flags)
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
<code>struct filename * old</code>
</li>
<li>
<b>Param added. </b>
<code>struct filename * new</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * oldname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * newname</code>
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
