# Function: <code>arch_tlb_gather_mmu</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "arch_tlb_gather_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886432,
      "name": "arch_tlb_gather_mmu",
      "external": true,
      "loc": "mm/memory.c:219",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:tlb_gather_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886432,
      "name": "arch_tlb_gather_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "arch_tlb_gather_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980576,
      "name": "arch_tlb_gather_mmu",
      "external": true,
      "loc": "mm/memory.c:220",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:tlb_gather_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980576,
      "name": "arch_tlb_gather_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "arch_tlb_gather_mmu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115392,
      "name": "arch_tlb_gather_mmu",
      "external": true,
      "loc": "mm/memory.c:219",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:tlb_gather_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115392,
      "name": "arch_tlb_gather_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "arch_tlb_gather_mmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581257749,
      "name": "arch_tlb_gather_mmu",
      "external": true,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_gather_mmu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256208,
      "name": "arch_tlb_gather_mmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather * tlb, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
