# Function: <code>__bpf_trace_block_bio_complete</code>

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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583560896,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560896,
      "name": "__bpf_trace_block_bio_complete",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681328,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681328,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870016,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870016,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972896,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972896,
      "name": "__bpf_trace_block_bio_complete",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:261",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362464,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476592,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:233",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476592,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511488,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:233",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511488,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584922912,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:233",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922912,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628432,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:256",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628432,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396064,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:256",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396064,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586642880,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:282",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586642880,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586913840,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:284",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586913840,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495792144,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495792144,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229147140,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229147140,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289978496,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289978496,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941632,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941632,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878576,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878576,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925392,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925392,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
```

```json
{
  "name": "__bpf_trace_block_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026784,
      "name": "__bpf_trace_block_bio_complete",
      "external": false,
      "loc": "include/trace/events/block.h:262",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026784,
      "name": "__bpf_trace_block_bio_complete",
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int error</code>
</li>
</ul>
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
void __bpf_trace_block_bio_complete(void * __data, struct request_queue * q, struct bio * bio, int error)
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
