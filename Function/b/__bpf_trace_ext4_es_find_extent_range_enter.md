# Function: <code>__bpf_trace_ext4_es_find_extent_range_enter</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603888,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603888,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775584,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775584,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878704,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878704,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191616,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2341",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191616,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288288,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2368",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288288,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312544,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2192",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312544,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583655744,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2192",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655744,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584223568,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2198",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223568,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584864992,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2235",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864992,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585089632,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2242",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585089632,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2239",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333136,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494531032,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494531032,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227992336,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227992336,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288338864,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288338864,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847440,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847440,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784592,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784592,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836320,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836320,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__bpf_trace_ext4_es_find_extent_range_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922928,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2313",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922928,
      "name": "__bpf_trace_ext4_es_find_extent_range_enter",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
```
</details>
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
void __bpf_trace_ext4_es_find_extent_range_enter(void * __data, struct inode * inode, ext4_lblk_t lblk)
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
