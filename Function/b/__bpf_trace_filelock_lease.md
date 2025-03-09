# Function: <code>__bpf_trace_filelock_lease</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581980256,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:115",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980256,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582068448,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068448,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582230112,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230112,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329744,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329744,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582618960,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618960,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582691376,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691376,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582721280,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721280,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583047920,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047920,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583525296,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583525296,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125024,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125024,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584351776,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351776,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570112,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570112,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493909688,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493909688,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227389428,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227389428,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287551424,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287551424,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298480,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298480,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236240,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236240,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582288960,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288960,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
```

```json
{
  "name": "__bpf_trace_filelock_lease",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367616,
      "name": "__bpf_trace_filelock_lease",
      "external": false,
      "loc": "include/trace/events/filelock.h:119",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367616,
      "name": "__bpf_trace_filelock_lease",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_trace_filelock_lease(void * __data, struct inode * inode, struct file_lock * fl)
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
