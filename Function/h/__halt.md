# Function: <code>__halt</code>

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
  "name": "__halt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860136,
      "name": "__halt",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:181",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/coco/tdx/tdx.c:tdx_safe_halt"
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
  "name": "__halt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862277,
      "name": "__halt",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:223",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/coco/tdx/tdx.c:tdx_safe_halt"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u64 __halt(const bool irq_disabled)
```

```json
{
  "name": "__halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596945040,
      "name": "__halt",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:229",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/coco/tdx/tdx.c:tdx_safe_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596945040,
      "name": "__halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
u64 __halt(const bool irq_disabled)
```

```json
{
  "name": "__halt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597872512,
      "name": "__halt",
      "external": false,
      "loc": "arch/x86/coco/tdx/tdx.c:253",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/coco/tdx/tdx.c:tdx_safe_halt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597872512,
      "name": "__halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
u64 __halt(const bool irq_disabled)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
