# Function: <code>move_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int move_huge_pmd(struct vm_area_struct * vma, struct vm_area_struct * new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904160,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1496",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904160,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030864,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1367",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030864,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd, bool * need_flush)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106048,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1486",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106048,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd, bool * need_flush)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155696,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1698",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155696,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd, bool * need_flush)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277536,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1782",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277536,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd, bool * need_flush)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426416,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1780",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426416,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512048,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1802",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512048,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1860",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633400,
      "name": "move_huge_pmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581621616,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692464,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692464,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909968,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1724",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909968,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955200,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1745",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955200,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980992,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1750",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980992,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582282976,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1668",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282976,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767072,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1673",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767072,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301616,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1768",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301616,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583520832,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1752",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520832,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583715856,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1968",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583715856,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493137576,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493137576,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286621424,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286621424,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661200,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661200,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601072,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601072,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652512,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652512,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```

```json
{
  "name": "move_huge_pmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718944,
      "name": "move_huge_pmd",
      "external": true,
      "loc": "mm/huge_memory.c:1865",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718944,
      "name": "move_huge_pmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * new_vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, new_vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code> ➡️ <code>vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * need_flush</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool * need_flush</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int old_end</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code> ➡️ <code>vma, old_addr, new_addr, old_pmd, new_pmd</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool move_huge_pmd(struct vm_area_struct * vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t * old_pmd, pmd_t * new_pmd)
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
