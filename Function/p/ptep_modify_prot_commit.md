# Function: <code>ptep_modify_prot_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580715277,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437765,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:472",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830667,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:445",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620709,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:445",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856004,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:436",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896244,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:436",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709101,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:436",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580901336,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940975,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755725,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:444",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998710,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041127,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912725,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581132492,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176603,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094061,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:430",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581214179,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259966,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189829,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581275055,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333692,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353196,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:435",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333855,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393100,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452092,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581531667,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:437",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591281,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:437",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041852,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:437",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748588,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:437",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581575319,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637297,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090812,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809982,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:403",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581597068,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658940,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115884,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838702,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581873016,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927212,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432268,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171726,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:426",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271190,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334271,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948819,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672470,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582763056,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835188,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506000,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279990,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:432",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582978587,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050408,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721363,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510150,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583154484,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232256,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922193,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730620,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:make_uffd_wp_pte",
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492753096,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798680,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226612664,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t old_pte, pte_t pte)
```

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282758816,
      "name": "ptep_modify_prot_commit",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:436",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282758816,
      "name": "ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272765484,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581302703,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361948,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420828,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581260442,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306342,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360043,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:658",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581293903,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353148,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411308,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581358047,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417084,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582490760,
      "name": "ptep_modify_prot_commit",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:423",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t old_pte, pte_t pte)
```
</details>
</li>
</ul>
