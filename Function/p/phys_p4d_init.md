# Function: <code>phys_p4d_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588292339,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:628",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588857461,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:628",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589236538,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:639",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589480382,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:636",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589939982,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590167537,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591185339,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:679",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185339,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591680692,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:674",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591680692,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591624184,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:674",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591624184,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592797511,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:675",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592797511,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594697503,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:674",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594697503,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596436208,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:675",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596436208,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 965
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596976960,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:675",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596976960,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597905392,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:675",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597905392,
      "name": "phys_p4d_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589769825,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589492774,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590213233,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
  "name": "phys_p4d_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590263601,
      "name": "phys_p4d_init",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:671",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int phys_p4d_init(p4d_t * p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init)
```
</details>
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
