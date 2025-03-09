# Function: <code>change_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580714207,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:62",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580829277,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:63",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895086,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:64",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580939810,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:36",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581040341,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:37",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175824,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175824,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581259222,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332912,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332912,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392320,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392320,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590624,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590624,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1455
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
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636640,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636640,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658288,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658288,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1439
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
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926560,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926560,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1490
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
long unsigned int change_pte_range(struct mmu_gather * tlb, struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333360,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:41",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333360,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2396
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
long unsigned int change_pte_range(struct mmu_gather * tlb, struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834256,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:83",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834256,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2505
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
long int change_pte_range(struct mmu_gather * tlb, struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049744,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:83",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049744,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2261
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
long int change_pte_range(struct mmu_gather * tlb, struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231552,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:83",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231552,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2111
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492798052,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226612440,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286169800,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272765170,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361168,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361168,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581305677,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352368,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352368,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```

```json
{
  "name": "change_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416304,
      "name": "change_pte_range",
      "external": false,
      "loc": "mm/mprotect.c:38",
      "file": "mm/mprotect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416304,
      "name": "change_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1238
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int dirty_accountable</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot_numa</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_gather * tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, pmd, addr, end, newprot, cp_flags</code> ➡️ <code>tlb, vma, pmd, addr, end, newprot, cp_flags</code>
</li>
</ul>
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
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct * vma, pmd_t * pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
