# Function: <code>vfs_statx</code>

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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296608,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:165",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat",
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64",
        "arch/x86/ia32/sys_ia32.c:sys32_stat64",
        "fs/stat.c:C_SYSC_newfstatat",
        "fs/stat.c:C_SYSC_newlstat",
        "fs/stat.c:C_SYSC_newstat",
        "fs/stat.c:SYSC_statx",
        "fs/stat.c:SYSC_newfstatat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296608,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436464,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:166",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:sys32_fstatat",
        "arch/x86/ia32/sys_ia32.c:sys32_lstat64",
        "arch/x86/ia32/sys_ia32.c:sys32_stat64",
        "fs/stat.c:C_SYSC_newfstatat",
        "fs/stat.c:C_SYSC_newlstat",
        "fs/stat.c:C_SYSC_newstat",
        "fs/stat.c:SYSC_statx",
        "fs/stat.c:SYSC_newfstatat",
        "fs/stat.c:SYSC_newlstat",
        "fs/stat.c:SYSC_newstat",
        "fs/stat.c:SYSC_lstat",
        "fs/stat.c:SYSC_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436464,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594496,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:166",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594496,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680480,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:166",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680480,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798608,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798608,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871200,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871200,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099328,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:192",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64",
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:do_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099328,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146064,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:166",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:do_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146064,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170912,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:184",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:do_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170912,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488208,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:202",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:do_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488208,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int vfs_statx(int dfd, struct filename * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009984,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:216",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:do_statx",
        "fs/stat.c:vfs_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009984,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int vfs_statx(int dfd, struct filename * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583572656,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:220",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:do_statx",
        "fs/stat.c:vfs_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572656,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int vfs_statx(int dfd, struct filename * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788736,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:226",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:do_statx",
        "fs/stat.c:vfs_fstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788736,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int vfs_statx(int dfd, struct filename * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994352,
      "name": "vfs_statx",
      "external": false,
      "loc": "fs/stat.c:232",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:do_statx",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994352,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493344344,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493344344,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226937356,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226937356,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286888672,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_fstatat64",
        "fs/stat.c:__do_sys_lstat64",
        "fs/stat.c:__do_sys_stat64",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286888672,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273073522,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273073522,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839936,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839936,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777600,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777600,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831248,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831248,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
```

```json
{
  "name": "vfs_statx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900640,
      "name": "vfs_statx",
      "external": true,
      "loc": "fs/stat.c:168",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_md.c:bstat",
        "init/initramfs.c:clean_path",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64",
        "arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64",
        "fs/stat.c:__do_compat_sys_newfstatat",
        "fs/stat.c:__do_compat_sys_newlstat",
        "fs/stat.c:__do_compat_sys_newstat",
        "fs/stat.c:__do_sys_statx",
        "fs/stat.c:__do_sys_newfstatat",
        "fs/stat.c:__do_sys_newlstat",
        "fs/stat.c:__do_sys_newstat",
        "fs/stat.c:__do_sys_lstat",
        "fs/stat.c:__do_sys_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900640,
      "name": "vfs_statx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int vfs_statx(int dfd, const char * filename, int flags, struct kstat * stat, u32 request_mask)
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char * filename</code> ➡️ <code>struct filename * filename</code>
</li>
</ul>
</details>
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
