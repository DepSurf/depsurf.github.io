# Function: <code>pgd_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:654",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580765849,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781721,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829416,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833631,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855940,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580864380,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580884951,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831417,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844393,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894984,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899742,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906348,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580926180,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580953031,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:691",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:21",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:22",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581503759,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521057,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593776,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596270,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609500,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631236,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:map_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720558,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:964",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581543919,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596036,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639792,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642494,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656892,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676494,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:map_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768462,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581567014,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618684,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661360,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664114,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678332,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698885,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795196,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:963",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pgd_bad(pgd_t pgd)
```

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581831815,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878920,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte"
      ]
    },
    {
      "addr": 18446744071581929720,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932468,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947547,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970679,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079175,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:934",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847184,
      "name": "pgd_bad",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582224992,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242631,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582337301,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340985,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582356840,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393852,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518901,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:932",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582714714,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738279,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838377,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842601,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858824,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900114,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037120,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:950",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582928781,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953864,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054482,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058348,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583074328,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115250,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246133,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583102912,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125934,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236114,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240060,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256376,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298146,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480661,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1173",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "arch/arm/mm/pgd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d-hack.h:28",
      "file": "mm/swapfile.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282842560,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286065108,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075120,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286169248,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286176748,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286187612,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286213384,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vunmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286345276,
      "name": "pgd_bad",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:979",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pgd_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable-nop4d.h:23",
      "file": "mm/swapfile.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int pgd_bad(pgd_t pgd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int pgd_bad(pgd_t pgd)
```
</details>
</li>
</ul>
