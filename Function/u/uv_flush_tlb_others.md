# Function: <code>uv_flush_tlb_others</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:29",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:29",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:29",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:30",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:31",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:31",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:37",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:37",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465216,
      "name": "uv_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/platform/uv/tlb_uv.c:1102",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465216,
      "name": "uv_flush_tlb_others",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486256,
      "name": "uv_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/platform/uv/tlb_uv.c:1102",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486256,
      "name": "uv_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:39",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:39",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv.h:39",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "uv_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470544,
      "name": "uv_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/platform/uv/tlb_uv.c:1102",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470544,
      "name": "uv_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1198
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
const struct cpumask * uv_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
