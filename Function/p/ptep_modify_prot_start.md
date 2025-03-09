# Function: <code>ptep_modify_prot_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580715132,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437748,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:461",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830525,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620686,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:434",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855912,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896102,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709078,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580901249,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940840,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755701,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:433",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998613,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040981,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912701,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581132344,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176427,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094044,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:419",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581214012,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259764,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189812,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274872,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333498,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353180,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:425",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333672,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392906,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452076,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581531480,
      "name": "ptep_modify_prot_start",
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
      "addr": 18446744071581591057,
      "name": "ptep_modify_prot_start",
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
      "addr": 18446744071582041845,
      "name": "ptep_modify_prot_start",
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
      "addr": 18446744071582748572,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:427",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581575128,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:393",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637073,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:393",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090805,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:393",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809966,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:393",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581596868,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658716,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115877,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838686,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581872823,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926988,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432261,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171710,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:416",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271018,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334043,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948813,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672455,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582762882,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835002,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505994,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584279975,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:422",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582978416,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050223,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721357,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510135,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583154193,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231989,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922187,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:clean_record_pte",
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730571,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:417",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492752964,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798540,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226612596,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
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
pte_t ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "ptep_modify_prot_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282758496,
      "name": "ptep_modify_prot_start",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:420",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282758496,
      "name": "ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272765444,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581302520,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361754,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420812,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581260303,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306176,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360032,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:647",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581293720,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352954,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411292,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
  "name": "ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357864,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416890,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582490744,
      "name": "ptep_modify_prot_start",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:413",
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
pte_t ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
</ul>
