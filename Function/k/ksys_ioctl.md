# Function: <code>ksys_ioctl</code>

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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664288,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:692",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664288,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750656,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:704",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750656,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868032,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:704",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868032,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940432,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940432,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171536,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:739",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171536,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493428880,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__arm64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493428880,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227008872,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__se_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227008872,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286986464,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__se_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286986464,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273129322,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__se_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273129322,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909168,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909168,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846752,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846752,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900480,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900480,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "ksys_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970096,
      "name": "ksys_ioctl",
      "external": true,
      "loc": "fs/ioctl.c:705",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:md_run_setup",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "init/do_mounts_md.c:md_setup_drive",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970096,
      "name": "ksys_ioctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
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
int ksys_ioctl(unsigned int fd, unsigned int cmd, long unsigned int arg)
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
