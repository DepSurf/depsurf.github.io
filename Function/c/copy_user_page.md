# Function: <code>copy_user_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580665061,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839275,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898565,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327059,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580802582,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966381,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035607,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050004,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498324,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867632,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040127,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110789,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132947,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582517,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912481,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088259,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160902,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173120,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644532,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:30",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011633,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200451,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286258,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309547,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790721,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581145370,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345746,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415757,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451216,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963599,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581225210,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429842,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499120,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534835,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045980,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581298881,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542576,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608716,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638064,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582210357,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357649,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607475,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679615,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709088,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582291253,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581555273,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822296,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926772,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566301,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581599679,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870312,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973792,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582637773,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581622527,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900920,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582002280,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582676671,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581889935,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195610,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582304040,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993793,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582287938,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659333,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793605,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583463774,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582780718,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332137,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584055326,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582974771,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281118,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583153010,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497918,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void copy_user_page(void * vto, void * vfrom, long unsigned int vaddr, struct page * pg)
```

```json
{
  "name": "copy_user_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282718032,
      "name": "copy_user_page",
      "external": true,
      "loc": "arch/powerpc/mm/mem.c:552",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282718032,
      "name": "copy_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581326497,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576211,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648351,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677824,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582259989,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581270257,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517779,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591180,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624500,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197203,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581317697,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567523,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639663,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669136,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582250469,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
  "name": "copy_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581381630,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632481,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706073,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735516,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582330769,
      "name": "copy_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:31",
      "file": "fs/dax.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void copy_user_page(void * vto, void * vfrom, long unsigned int vaddr, struct page * pg)
```
</details>
</li>
</ul>
