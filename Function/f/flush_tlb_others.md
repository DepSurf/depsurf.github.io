# Function: <code>flush_tlb_others</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579314279,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:333",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_current_task",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_page"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579314757,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:323",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_current_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840051,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:323",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_flush"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579330032,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:314",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_current_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910599,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:314",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_flush"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579323760,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:314",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579348744,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:306",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579360456,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:306",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579387968,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403434,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579406682,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417273,
      "name": "flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:890",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416176,
      "name": "flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579417353,
      "name": "flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:826",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416256,
      "name": "flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
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
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402522,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579331962,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402442,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_others",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579411281,
      "name": "flush_tlb_others",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:65",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
</ul>
