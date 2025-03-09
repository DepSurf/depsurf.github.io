# Function: <code>bpf_kprobe_multi_link_attach</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_kprobe_multi_link_attach(const union bpf_attr * attr, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_kprobe_multi_link_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310304,
      "name": "bpf_kprobe_multi_link_attach",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2456",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310304,
      "name": "bpf_kprobe_multi_link_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
int bpf_kprobe_multi_link_attach(const union bpf_attr * attr, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_kprobe_multi_link_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638672,
      "name": "bpf_kprobe_multi_link_attach",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2756",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638672,
      "name": "bpf_kprobe_multi_link_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
int bpf_kprobe_multi_link_attach(const union bpf_attr * attr, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_kprobe_multi_link_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780112,
      "name": "bpf_kprobe_multi_link_attach",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2786",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780112,
      "name": "bpf_kprobe_multi_link_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int bpf_kprobe_multi_link_attach(const union bpf_attr * attr, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_kprobe_multi_link_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900064,
      "name": "bpf_kprobe_multi_link_attach",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2945",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900064,
      "name": "bpf_kprobe_multi_link_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1292
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
int bpf_kprobe_multi_link_attach(const union bpf_attr * attr, struct bpf_prog * prog)
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
