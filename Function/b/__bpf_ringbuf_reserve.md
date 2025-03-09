# Function: <code>__bpf_ringbuf_reserve</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065328,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:330",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065328,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077008,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:308",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077008,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092000,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:305",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092000,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321184,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:305",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321184,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623632,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:305",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623632,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582009248,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:391",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009248,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200128,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:409",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200128,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
```

```json
{
  "name": "__bpf_ringbuf_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349360,
      "name": "__bpf_ringbuf_reserve",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:405",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349360,
      "name": "__bpf_ringbuf_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * __bpf_ringbuf_reserve(struct bpf_ringbuf * rb, u64 size)
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
