# Function: <code>vfs_statx_fd</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296480,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:131",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64",
        "fs/stat.c:C_SYSC_newfstat",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296480,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436336,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:132",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:sys32_fstat64",
        "fs/stat.c:C_SYSC_newfstat",
        "fs/stat.c:SYSC_newfstat",
        "fs/stat.c:SYSC_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436336,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594352,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:132",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594352,
      "name": "vfs_statx_fd",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680336,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:132",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680336,
      "name": "vfs_statx_fd",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798464,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798464,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871056,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871056,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101152,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:140",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101152,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493344168,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493344168,
      "name": "vfs_statx_fd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226937228,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226937228,
      "name": "vfs_statx_fd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286888448,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_fstat64",
        "fs/stat.c:__do_sys_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286888448,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273073390,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_sys_newfstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273073390,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839792,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839792,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777456,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777456,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831104,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831104,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```

```json
{
  "name": "vfs_statx_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900496,
      "name": "vfs_statx_fd",
      "external": true,
      "loc": "fs/stat.c:134",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64",
        "fs/stat.c:__do_compat_sys_newfstat",
        "fs/stat.c:__do_sys_newfstat",
        "fs/stat.c:__do_sys_fstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900496,
      "name": "vfs_statx_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
```
</details>
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
int vfs_statx_fd(unsigned int fd, struct kstat * stat, u32 request_mask, unsigned int query_flags)
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
