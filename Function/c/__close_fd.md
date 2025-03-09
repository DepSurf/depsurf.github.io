# Function: <code>__close_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116880,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:634",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116880,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282608,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:635",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282608,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361024,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:635",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361024,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416288,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416288,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557824,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:625",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557824,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712816,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:620",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712816,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799328,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:620",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799328,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918144,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918144,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990528,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990528,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224320,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:626",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224320,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493502864,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__arm64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493502864,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227061580,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__se_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227061580,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287067344,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__se_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287067344,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273176944,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__se_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273176944,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959264,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959264,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896832,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896832,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950576,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950576,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
```

```json
{
  "name": "__close_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018864,
      "name": "__close_fd",
      "external": true,
      "loc": "fs/file.c:621",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/initramfs.c:do_copy",
        "fs/open.c:__ia32_sys_close",
        "fs/open.c:__x64_sys_close",
        "fs/file.c:replace_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018864,
      "name": "__close_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int __close_fd(struct files_struct * files, unsigned int fd)
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
