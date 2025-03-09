# Function: <code>fd_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211760,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs",
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/compat.c:C_SYSC_fstatfs",
        "fs/compat.c:C_SYSC_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211760,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376448,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_fstatfs",
        "fs/compat.c:C_SYSC_fstatfs64",
        "fs/compat.c:C_SYSC_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376448,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454192,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:95",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_fstatfs",
        "fs/compat.c:C_SYSC_fstatfs64",
        "fs/compat.c:C_SYSC_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454192,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509920,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:98",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs64",
        "fs/statfs.c:C_SYSC_fstatfs",
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509920,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652544,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:99",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs64",
        "fs/statfs.c:C_SYSC_fstatfs",
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652544,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815680,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:99",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815680,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902496,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:99",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902496,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028048,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028048,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105984,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105984,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342800,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342800,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394320,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394320,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421616,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421616,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744432,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744432,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291312,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291312,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875200,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875200,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584096960,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096960,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313104,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:115",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313104,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493644560,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493644560,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227180696,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_sys_fstatfs64",
        "fs/statfs.c:__se_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227180696,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287235952,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287235952,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273277812,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273277812,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074720,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074720,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012272,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012272,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066000,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066000,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int fd_statfs(int fd, struct kstatfs * st)
```

```json
{
  "name": "fd_statfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137744,
      "name": "fd_statfs",
      "external": true,
      "loc": "fs/statfs.c:113",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137744,
      "name": "fd_statfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
