# Function: <code>update_page_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291872,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:59",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291872,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291408,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:59",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291408,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306832,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:59",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306832,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304592,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:60",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304592,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326336,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:60",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326336,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337312,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:61",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337312,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363856,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:72",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363856,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378416,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378416,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382704,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382704,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422640,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:80",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422640,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422336,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:80",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422336,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425392,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:82",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425392,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489024,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:82",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489024,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569072,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:85",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569072,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677344,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:86",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677344,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691200,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:87",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691200,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725728,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:87",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725728,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297808588,
      "name": "update_page_count",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:176",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:create_physical_mapping"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378608,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378608,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308448,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308448,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378528,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378528,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void update_page_count(int level, long unsigned int pages)
```

```json
{
  "name": "update_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387008,
      "name": "update_page_count",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:73",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387008,
      "name": "update_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
void update_page_count(int level, long unsigned int pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void update_page_count(int level, long unsigned int pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void update_page_count(int level, long unsigned int pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void update_page_count(int level, long unsigned int pages)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
