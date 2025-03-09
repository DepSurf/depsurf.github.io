# Function: <code>bpf_task_fd_query_copy</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628656,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2143",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628656,
      "name": "bpf_task_fd_query_copy.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687760,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2462",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687760,
      "name": "bpf_task_fd_query_copy.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580754880,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2688",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754880,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805504,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805504,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926096,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3657",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926096,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922288,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3828",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922288,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925856,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3852",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925856,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128080,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4035",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128080,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402432,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4296",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402432,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753376,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4344",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753376,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913312,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4481",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913312,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038992,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4818",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038992,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492124088,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492124088,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2472
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
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226023332,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226023332,
      "name": "bpf_task_fd_query_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285330576,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285330576,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272293572,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272293572,
      "name": "bpf_task_fd_query_copy.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580774304,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774304,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580720480,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720480,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765552,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765552,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_task_fd_query_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580823712,
      "name": "bpf_task_fd_query_copy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2713",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823712,
      "name": "bpf_task_fd_query_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int bpf_task_fd_query_copy(const union bpf_attr * attr, union bpf_attr * uattr, u32 prog_id, u32 fd_type, const char * buf, u64 probe_offset, u64 probe_addr)
```
</details>
</li>
</ul>
