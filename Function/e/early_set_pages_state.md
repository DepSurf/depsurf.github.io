# Function: <code>early_set_pages_state</code>

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
void early_set_pages_state(long unsigned int paddr, unsigned int npages, enum psc_op op)
```

```json
{
  "name": "early_set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617056088,
      "name": "early_set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:663",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:early_snp_set_memory_shared",
        "arch/x86/kernel/sev.c:early_snp_set_memory_private"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617056088,
      "name": "early_set_pages_state",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 243
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
void early_set_pages_state(long unsigned int paddr, unsigned int npages, enum psc_op op)
```

```json
{
  "name": "early_set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627702560,
      "name": "early_set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:663",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_prep_memory",
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627702560,
      "name": "early_set_pages_state",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 248
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
void early_set_pages_state(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages, enum psc_op op)
```

```json
{
  "name": "early_set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631760,
      "name": "early_set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:658",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_prep_memory",
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631760,
      "name": "early_set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void early_set_pages_state(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages, enum psc_op op)
```

```json
{
  "name": "early_set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661440,
      "name": "early_set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:685",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_prep_memory",
        "arch/x86/kernel/sev.c:snp_prep_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661440,
      "name": "early_set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void early_set_pages_state(long unsigned int paddr, unsigned int npages, enum psc_op op)
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
<code>long unsigned int vaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>paddr, npages, op</code> ➡️ <code>vaddr, paddr, npages, op</code>
</li>
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
