# Function: <code>process_vm_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748880,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:247",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:SyS_process_vm_readv",
        "mm/process_vm_access.c:SyS_process_vm_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748880,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868048,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:252",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:SyS_process_vm_writev",
        "mm/process_vm_access.c:SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868048,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935952,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:259",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:SyS_process_vm_writev",
        "mm/process_vm_access.c:SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935952,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979840,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:260",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:SyS_process_vm_writev",
        "mm/process_vm_access.c:SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979840,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082576,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:260",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:SyS_process_vm_writev",
        "mm/process_vm_access.c:SyS_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082576,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221600,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:258",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221600,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305312,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:258",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305312,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385120,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385120,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446064,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446064,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651568,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:256",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651568,
      "name": "process_vm_rw",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699312,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699312,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721024,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:253",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721024,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993312,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:253",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993312,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416224,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:253",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416224,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924096,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:253",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924096,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140496,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:253",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140496,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323616,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323616,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492852520,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__arm64_sys_process_vm_writev",
        "mm/process_vm_access.c:__arm64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492852520,
      "name": "process_vm_rw",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226653608,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__se_sys_process_vm_writev",
        "mm/process_vm_access.c:__se_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226653608,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286240400,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__se_sys_process_vm_writev",
        "mm/process_vm_access.c:__se_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286240400,
      "name": "process_vm_rw",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272800484,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__se_sys_process_vm_writev",
        "mm/process_vm_access.c:__se_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272800484,
      "name": "process_vm_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414912,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414912,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357424,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357424,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406112,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406112,
      "name": "process_vm_rw",
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
ssize_t process_vm_rw(pid_t pid, const struct iovec * lvec, long unsigned int liovcnt, const struct iovec * rvec, long unsigned int riovcnt, long unsigned int flags, int vm_write)
```

```json
{
  "name": "process_vm_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470224,
      "name": "process_vm_rw",
      "external": false,
      "loc": "mm/process_vm_access.c:254",
      "file": "mm/process_vm_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:__ia32_sys_process_vm_writev",
        "mm/process_vm_access.c:__x64_sys_process_vm_writev",
        "mm/process_vm_access.c:__ia32_sys_process_vm_readv",
        "mm/process_vm_access.c:__x64_sys_process_vm_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470224,
      "name": "process_vm_rw",
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
