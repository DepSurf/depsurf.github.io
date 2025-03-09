# Function: <code>bpf_ringbuf_commit</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066725,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:392",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065680,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078341,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:370",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077360,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581093321,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:370",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092384,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322505,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:370",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321568,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581625616,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:370",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624064,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582012064,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:456",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009664,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582203088,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:474",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200560,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
```

```json
{
  "name": "bpf_ringbuf_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582352320,
      "name": "bpf_ringbuf_commit",
      "external": false,
      "loc": "kernel/bpf/ringbuf.c:470",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349792,
      "name": "bpf_ringbuf_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void bpf_ringbuf_commit(void * sample, u64 flags, bool discard)
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
