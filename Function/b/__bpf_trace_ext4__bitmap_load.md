# Function: <code>__bpf_trace_ext4__bitmap_load</code>

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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582503616,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1239",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503616,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603808,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603808,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775504,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775504,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878624,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878624,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1285",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196576,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1296",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292560,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1296",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316624,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1296",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660144,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1302",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230176,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1304",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873136,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1311",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100320,
      "name": "__bpf_trace_ext4__bitmap_load",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1308",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332640,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494530912,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494530912,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227992080,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227992080,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288338624,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288338624,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847360,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847360,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784512,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784512,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836240,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836240,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
```

```json
{
  "name": "__bpf_trace_ext4__bitmap_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922848,
      "name": "__bpf_trace_ext4__bitmap_load",
      "external": false,
      "loc": "include/trace/events/ext4.h:1260",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922848,
      "name": "__bpf_trace_ext4__bitmap_load",
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
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
void __bpf_trace_ext4__bitmap_load(void * __data, struct super_block * sb, long unsigned int group)
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
