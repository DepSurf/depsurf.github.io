# Function: <code>pfn_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890031,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:360",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894089,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:360",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580787438,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020579,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036049,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050630,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580851734,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095179,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111227,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133588,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585151,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:389",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897048,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:520",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141985,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:520",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159905,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:520",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173735,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:520",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646076,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:520",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995602,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:535",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264224,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:535",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293629,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:535",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310028,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:535",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791655,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:535",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579335055,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369061,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581129660,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194547,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411196,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440715,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451698,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964100,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:554",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579361599,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396517,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581209407,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277923,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494617,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524139,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535333,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048759,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:556",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579376191,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411900,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581284355,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352388,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602516,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633069,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645387,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205690,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380479,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415084,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581343075,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411892,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673204,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704109,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717087,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286538,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579419166,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444431,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517797,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612022,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891732,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920138,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935986,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575946,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:612",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579419838,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442032,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563533,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659350,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937780,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966826,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978528,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647342,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422445,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444909,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603885,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680003,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963270,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994918,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006546,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673691,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:611",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579486073,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509709,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870092,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949283,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297110,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308972,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999979,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:582",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579555278,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565868,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593297,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265364,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358675,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784943,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582805173,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468700,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:585",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596434328,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662097,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674030,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704475,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756790,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860902,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317904,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338763,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061497,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:602",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596975073,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676273,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687918,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717963,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972604,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077959,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536401,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557871,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287932,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:603",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597903505,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710401,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722446,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752531,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150356,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260215,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730321,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757699,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504732,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:772",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
pmd_t pfn_pmd(long unsigned int pfn, pgprot_t pgprot)
```

```json
{
  "name": "pfn_pmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282757056,
      "name": "pfn_pmd",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:128",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/pgtable.c:mk_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282756976,
      "name": "pfn_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
  "name": "pfn_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270612544,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:68",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:create_pgd_mapping",
        "arch/riscv/mm/init.c:create_pgd_mapping",
        "arch/riscv/mm/init.c:setup_vm",
        "arch/riscv/mm/init.c:setup_vm"
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579376383,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410924,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581311923,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380740,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641940,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672845,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685823,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255274,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579306416,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339865,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255640,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323383,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582873,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612308,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624899,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582199784,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579376303,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410844,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581303123,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371940,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633252,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664157,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677135,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245754,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
  "name": "pfn_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384783,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419708,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581367101,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435828,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699588,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730525,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743772,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328512,
      "name": "pfn_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:573",
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
pmd_t pfn_pmd(long unsigned int pfn, pgprot_t pgprot)
```
</details>
</li>
</ul>
