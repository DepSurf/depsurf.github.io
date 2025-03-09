# Function: <code>__bpf_trace_ext4_forget</code>

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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503872,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1117",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503872,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604064,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604064,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775936,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775936,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879056,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879056,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191728,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1163",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191728,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288400,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1174",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288400,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312656,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1174",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312656,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583655856,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1174",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655856,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584223824,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1180",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223824,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584865376,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1182",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865376,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585090016,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1189",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090016,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585321872,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1186",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321872,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494531304,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494531304,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227993032,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227993032,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288339920,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288339920,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847792,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847792,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784944,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784944,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836672,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836672,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
```

```json
{
  "name": "__bpf_trace_ext4_forget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923280,
      "name": "__bpf_trace_ext4_forget",
      "external": false,
      "loc": "include/trace/events/ext4.h:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923280,
      "name": "__bpf_trace_ext4_forget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
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
void __bpf_trace_ext4_forget(void * __data, struct inode * inode, int is_metadata, __u64 block)
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
