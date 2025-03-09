# Function: <code>__bpf_trace_ext4__es_shrink_enter</code>

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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582504016,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2381",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504016,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582604208,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604208,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776096,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776096,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879216,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879216,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2449",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583196800,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2476",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292784,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2300",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316832,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2300",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660352,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2306",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230592,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2343",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584873824,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2350",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101008,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2347",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333328,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494531544,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494531544,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227993560,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227993560,
      "name": "__bpf_trace_ext4__es_shrink_enter",
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288340416,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288340416,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847952,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847952,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582785104,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785104,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836832,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836832,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
```

```json
{
  "name": "__bpf_trace_ext4__es_shrink_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923440,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "external": false,
      "loc": "include/trace/events/ext4.h:2421",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923440,
      "name": "__bpf_trace_ext4__es_shrink_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
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
void __bpf_trace_ext4__es_shrink_enter(void * __data, struct super_block * sb, int nr_to_scan, int cache_cnt)
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
