# Function: <code>build_body</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int build_body(struct jit_ctx * ctx, bool extra_pass)
```

```json
{
  "name": "build_body",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490371400,
      "name": "build_body",
      "external": false,
      "loc": "arch/arm64/net/bpf_jit_comp.c:778",
      "file": "arch/arm64/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490371400,
      "name": "build_body",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int build_body(struct jit_ctx * ctx)
```

```json
{
  "name": "build_body",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224552416,
      "name": "build_body",
      "external": false,
      "loc": "arch/arm/net/bpf_jit_32.c:1807",
      "file": "arch/arm/net/bpf_jit_32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile",
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224552416,
      "name": "build_body",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int build_body(struct rv_jit_context * ctx, bool extra_pass)
```

```json
{
  "name": "build_body",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271375542,
      "name": "build_body",
      "external": false,
      "loc": "arch/riscv/net/bpf_jit_comp.c:1517",
      "file": "arch/riscv/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271375542,
      "name": "build_body",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int build_body(struct jit_ctx * ctx, bool extra_pass)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int build_body(struct jit_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int build_body(struct rv_jit_context * ctx, bool extra_pass)
```
</details>
</li>
</ul>
