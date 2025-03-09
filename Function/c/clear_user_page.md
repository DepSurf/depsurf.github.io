# Function: <code>clear_user_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580688539,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898856,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327236,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580802062,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050290,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498644,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867143,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133243,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582255,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912099,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173342,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643982,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:24",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011085,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309745,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789716,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581144747,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451405,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963803,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581224571,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535023,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046140,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581298233,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638242,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582210525,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357001,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709266,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582291421,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581554599,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926967,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574767,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581599383,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973954,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582646285,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581622232,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582002442,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582676387,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581889624,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582304202,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993669,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582108410,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582287401,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793730,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583463560,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582582443,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780217,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332263,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584055112,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582789681,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582996650,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583551885,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584280904,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582964554,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583167882,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583746396,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584497704,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
void clear_user_page(void * page, long unsigned int vaddr, struct page * pg)
```

```json
{
  "name": "clear_user_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282716848,
      "name": "clear_user_page",
      "external": true,
      "loc": "arch/powerpc/mm/mem.c:539",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282716848,
      "name": "clear_user_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581325849,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678002,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582260157,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581269609,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624644,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196913,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581317049,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669314,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582250637,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
  "name": "clear_user_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581380980,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735729,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582330971,
      "name": "clear_user_page",
      "external": false,
      "loc": "arch/x86/include/asm/page.h:25",
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
void clear_user_page(void * page, long unsigned int vaddr, struct page * pg)
```
</details>
</li>
</ul>
