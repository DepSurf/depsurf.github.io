# Function: <code>compat_process_vm_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749168,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:305",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_SyS_process_vm_readv",
        "mm/process_vm_access.c:compat_SyS_process_vm_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749168,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868336,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:310",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_SyS_process_vm_writev",
        "mm/process_vm_access.c:compat_SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868336,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936240,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:317",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_SyS_process_vm_writev",
        "mm/process_vm_access.c:compat_SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936240,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980192,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:318",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_SyS_process_vm_writev",
        "mm/process_vm_access.c:compat_SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980192,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082928,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:318",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:compat_SyS_process_vm_writev",
        "mm/process_vm_access.c:compat_SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082928,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222080,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:316",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222080,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305792,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:316",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305792,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385616,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385616,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446560,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446560,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651152,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:314",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651152,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492852960,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__arm64_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__arm64_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492852960,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286240864,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__se_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__se_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286240864,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415408,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415408,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357920,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357920,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406608,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406608,
      "name": "compat_process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "compat_process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470720,
      "name": "compat_process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:312",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_writev",
        "mm/process_vm_access.c:__x32_compat_sys_process_vm_readv",
        "mm/process_vm_access.c:__ia32_compat_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470720,
      "name": "compat_process_vm_rw",
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
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
ssize_t compat_process_vm_rw(compat_pid_t pid, const struct compat_iovec * lvec, long unsigned int liovcnt, const struct compat_iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
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
