# Function: <code>bpf_dynptr_set_null</code>

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
void bpf_dynptr_set_null(struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "bpf_dynptr_set_null",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581566000,
      "name": "bpf_dynptr_set_null",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1452",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566000,
      "name": "bpf_dynptr_set_null",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_dynptr_set_null(struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "bpf_dynptr_set_null",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939280,
      "name": "bpf_dynptr_set_null",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1436",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939280,
      "name": "bpf_dynptr_set_null",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_dynptr_set_null(struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "bpf_dynptr_set_null",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123280,
      "name": "bpf_dynptr_set_null",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1472",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_clone",
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "net/core/filter.c:bpf_dynptr_from_xdp",
        "net/core/filter.c:bpf_dynptr_from_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123280,
      "name": "bpf_dynptr_set_null",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_dynptr_set_null(struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "bpf_dynptr_set_null",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263824,
      "name": "bpf_dynptr_set_null",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1491",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_dynptr_clone",
        "kernel/bpf/helpers.c:bpf_dynptr_from_mem",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr",
        "net/core/filter.c:bpf_dynptr_from_xdp",
        "net/core/filter.c:bpf_dynptr_from_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263824,
      "name": "bpf_dynptr_set_null",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bpf_dynptr_set_null(struct bpf_dynptr_kern * ptr)
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
