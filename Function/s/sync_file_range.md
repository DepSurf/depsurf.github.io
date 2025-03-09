# Function: <code>sync_file_range</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016768,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016768,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094720,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094720,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331856,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:241",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331856,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383280,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:241",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383280,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410560,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:240",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410560,
      "name": "sync_file_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732944,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:241",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732944,
      "name": "sync_file_range",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278240,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:228",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "io_uring/io_uring.c:io_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278240,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860976,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:228",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "io_uring/sync.c:io_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860976,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082736,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:228",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "io_uring/sync.c:io_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082736,
      "name": "sync_file_range",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298848,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:228",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range",
        "io_uring/sync.c:io_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298848,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493630800,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493630800,
      "name": "sync_file_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227170980,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227170980,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287221520,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287221520,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273270762,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273270762,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063456,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063456,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001008,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001008,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054736,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054736,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126416,
      "name": "sync_file_range",
      "external": true,
      "loc": "fs/sync.c:238",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:ksys_sync_file_range",
        "fs/io_uring.c:__io_submit_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126416,
      "name": "sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sync_file_range(struct file * file, loff_t offset, loff_t nbytes, unsigned int flags)
```
</details>
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
