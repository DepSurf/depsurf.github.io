# Function: <code>pin_pagetable_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594976176,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1097",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_release_pte_init",
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594976176,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595139020,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1098",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_release_pte_init",
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595139020,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595381702,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu.c:1098",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_release_pte_init",
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595381702,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596302867,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1070",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596302867,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602620637,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1043",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602620637,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 139
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602788880,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1072",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602788880,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604583208,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604583208,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604678491,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604678491,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604690958,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604690958,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609042156,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609042156,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612105512,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:987",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612105512,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614245267,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:987",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614245267,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615165343,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:987",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615165343,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616931343,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:993",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616931343,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 171
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627535488,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:993",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627535488,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619281792,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1002",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619281792,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621574352,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1002",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621574352,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604617239,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604617239,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604695054,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604695054,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```

```json
{
  "name": "pin_pagetable_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604695010,
      "name": "pin_pagetable_pfn",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1082",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_release_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604695010,
      "name": "pin_pagetable_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 131
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn)
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
