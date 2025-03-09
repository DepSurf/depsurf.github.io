# Function: <code>__bpf_dynptr_size</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 __bpf_dynptr_size(const struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "__bpf_dynptr_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128559,
      "name": "__bpf_dynptr_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1446",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_size",
        "kernel/bpf/helpers.c:bpf_dynptr_adjust",
        "kernel/bpf/helpers.c:bpf_dynptr_slice",
        "kernel/bpf/helpers.c:bpf_dynptr_data",
        "kernel/bpf/helpers.c:bpf_dynptr_write",
        "kernel/bpf/helpers.c:bpf_dynptr_read"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123120,
      "name": "__bpf_dynptr_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u32 __bpf_dynptr_size(const struct bpf_dynptr_kern * ptr)
```

```json
{
  "name": "__bpf_dynptr_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582269791,
      "name": "__bpf_dynptr_size",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1465",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_dynptr_size",
        "kernel/bpf/helpers.c:bpf_dynptr_adjust",
        "kernel/bpf/helpers.c:bpf_dynptr_slice",
        "kernel/bpf/helpers.c:bpf_dynptr_data",
        "kernel/bpf/helpers.c:bpf_dynptr_write",
        "kernel/bpf/helpers.c:bpf_dynptr_read"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_file_xattr",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature",
        "fs/verity/measure.c:bpf_get_fsverity_digest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263664,
      "name": "__bpf_dynptr_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
u32 __bpf_dynptr_size(const struct bpf_dynptr_kern * ptr)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
