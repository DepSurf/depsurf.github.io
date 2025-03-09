# Function: <code>bpf_register_prog_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list * tl)
```

```json
{
  "name": "bpf_register_prog_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366064,
      "name": "bpf_register_prog_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:438",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366064,
      "name": "bpf_register_prog_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list * tl)
```

```json
{
  "name": "bpf_register_prog_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580423936,
      "name": "bpf_register_prog_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:535",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423936,
      "name": "bpf_register_prog_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list * tl)
```

```json
{
  "name": "bpf_register_prog_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472128,
      "name": "bpf_register_prog_type",
      "external": true,
      "loc": "kernel/bpf/syscall.c:576",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "kernel/trace/bpf_trace.c:register_kprobe_prog_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops",
        "net/core/filter.c:register_sk_filter_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472128,
      "name": "bpf_register_prog_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list * tl)
```
</details>
</li>
</ul>
