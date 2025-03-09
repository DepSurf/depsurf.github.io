# Function: <code>pvalidate_pages</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pvalidate_pages(long unsigned int vaddr, unsigned int npages, bool validate)
```

```json
{
  "name": "pvalidate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517456,
      "name": "pvalidate_pages",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:646",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:early_snp_set_memory_shared",
        "arch/x86/kernel/sev.c:early_snp_set_memory_private"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517456,
      "name": "pvalidate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pvalidate_pages(long unsigned int vaddr, unsigned int npages, bool validate)
```

```json
{
  "name": "pvalidate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579617008,
      "name": "pvalidate_pages",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:646",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:snp_prep_memory",
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617008,
      "name": "pvalidate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pvalidate_pages(struct snp_psc_desc * desc)
```

```json
{
  "name": "pvalidate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626752,
      "name": "pvalidate_pages",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:998",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:__set_pages_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626752,
      "name": "pvalidate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void pvalidate_pages(struct snp_psc_desc * desc)
```

```json
{
  "name": "pvalidate_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656128,
      "name": "pvalidate_pages",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:1074",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:__set_pages_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656128,
      "name": "pvalidate_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void pvalidate_pages(long unsigned int vaddr, unsigned int npages, bool validate)
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
<b>Param added. </b>
<code>struct snp_psc_desc * desc</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int vaddr</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int npages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool validate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
