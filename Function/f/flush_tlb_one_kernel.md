# Function: <code>flush_tlb_one_kernel</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416624,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1051",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416624,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416704,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:987",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416704,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419792,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1031",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419792,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483344,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1090",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "mm/kfence/core.c:kfence_unprotect",
        "mm/kfence/core.c:kfence_protect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483344,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562448,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1064",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "mm/kfence/core.c:kfence_protect_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562448,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669952,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1088",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "mm/kfence/core.c:kfence_protect_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669952,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683904,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1109",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "mm/kfence/core.c:kfence_init_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683904,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void flush_tlb_one_kernel(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718400,
      "name": "flush_tlb_one_kernel",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1111",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:set_pte_vaddr_pud",
        "arch/x86/mm/init_64.c:set_pte_vaddr_p4d",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/tlb.c:do_kernel_range_flush",
        "arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718400,
      "name": "flush_tlb_one_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void flush_tlb_one_kernel(long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
