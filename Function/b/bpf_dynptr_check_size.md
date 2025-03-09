# Function: <code>bpf_dynptr_check_size</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_dynptr_check_size(u32 size)
```

```json
{
  "name": "bpf_dynptr_check_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581566041,
      "name": "bpf_dynptr_check_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1438",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565920,
      "name": "bpf_dynptr_check_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int bpf_dynptr_check_size(u32 size)
```

```json
{
  "name": "bpf_dynptr_check_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581939337,
      "name": "bpf_dynptr_check_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1422",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939168,
      "name": "bpf_dynptr_check_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int bpf_dynptr_check_size(u32 size)
```

```json
{
  "name": "bpf_dynptr_check_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123337,
      "name": "bpf_dynptr_check_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1458",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123168,
      "name": "bpf_dynptr_check_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int bpf_dynptr_check_size(u32 size)
```

```json
{
  "name": "bpf_dynptr_check_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582263881,
      "name": "bpf_dynptr_check_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1477",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem"
      ],
      "caller_func": [
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263712,
      "name": "bpf_dynptr_check_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int bpf_dynptr_check_size(u32 size)
```
</details>
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
