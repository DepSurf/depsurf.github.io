# Function: <code>_tdx_hypercall</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_tdx_hypercall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578859291,
      "name": "_tdx_hypercall",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:50",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:handle_io",
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/coco/tdx/tdx.c:handle_mmio"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_tdx_hypercall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861355,
      "name": "_tdx_hypercall",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:52",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:handle_io",
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/coco/tdx/tdx.c:handle_mmio"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 _tdx_hypercall(u64 fn, u64 r12, u64 r13, u64 r14, u64 r15)
```

```json
{
  "name": "_tdx_hypercall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578858866,
      "name": "_tdx_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/shared/tdx.h:58",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:handle_io"
      ],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856288,
      "name": "_tdx_hypercall",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
u64 _tdx_hypercall(u64 fn, u64 r12, u64 r13, u64 r14, u64 r15)
```

```json
{
  "name": "_tdx_hypercall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856976,
      "name": "_tdx_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/shared/tdx.h:104",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_io",
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856976,
      "name": "_tdx_hypercall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
u64 _tdx_hypercall(u64 fn, u64 r12, u64 r13, u64 r14, u64 r15)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
