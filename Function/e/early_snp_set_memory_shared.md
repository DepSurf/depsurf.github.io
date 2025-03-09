# Function: <code>early_snp_set_memory_shared</code>

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
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, unsigned int npages)
```

```json
{
  "name": "early_snp_set_memory_shared",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617058030,
      "name": "early_snp_set_memory_shared",
      "external": true,
      "loc": "arch/x86/kernel/sev.c:723",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/kernel/sev.c:snp_prep_memory",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:snp_memcpy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617058030,
      "name": "early_snp_set_memory_shared",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, unsigned int npages)
```

```json
{
  "name": "early_snp_set_memory_shared",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627703997,
      "name": "early_snp_set_memory_shared",
      "external": true,
      "loc": "arch/x86/kernel/sev.c:723",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ],
      "caller_func": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:snp_memcpy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627703824,
      "name": "early_snp_set_memory_shared",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages)
```

```json
{
  "name": "early_snp_set_memory_shared",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619461361,
      "name": "early_snp_set_memory_shared",
      "external": true,
      "loc": "arch/x86/kernel/sev.c:734",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ],
      "caller_func": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:snp_memcpy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619461216,
      "name": "early_snp_set_memory_shared",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages)
```

```json
{
  "name": "early_snp_set_memory_shared",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621757649,
      "name": "early_snp_set_memory_shared",
      "external": true,
      "loc": "arch/x86/kernel/sev.c:761",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ],
      "caller_func": [
        "arch/x86/kernel/head64.c:__startup_64",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:snp_memcpy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621757504,
      "name": "early_snp_set_memory_shared",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, unsigned int npages)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
