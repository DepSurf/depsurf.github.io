# Function: <code>xen_free_ro_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594978317,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1131",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594978317,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 76
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595141062,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1132",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595141062,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 73
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595383744,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1132",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595383744,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 73
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596305040,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1104",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596305040,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602622922,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1077",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602622922,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602791688,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1106",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602791688,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604585553,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604585553,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604680954,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604680954,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604693399,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604693399,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609044380,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609044380,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612107736,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1020",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612107736,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614247449,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1020",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614247449,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615167571,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1020",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615167571,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616933574,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1026",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616933574,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627539981,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1026",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
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
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619286151,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1035",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
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
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621578647,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1035",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604619680,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604619680,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604697495,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604697495,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```

```json
{
  "name": "xen_free_ro_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604697501,
      "name": "xen_free_ro_pages",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1116",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604697501,
      "name": "xen_free_ro_pages",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 78
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size)
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
