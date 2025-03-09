# Function: <code>ioremap_pud_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582953649,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:97",
      "file": "lib/ioremap.c",
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583241220,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:97",
      "file": "lib/ioremap.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583356532,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:97",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588205452,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:104",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588754501,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:106",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589132627,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:106",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589367234,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:138",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589824112,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589824112,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590050336,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590050336,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, pgtbl_mod_mask * mask)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044768,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:150",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044768,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581697041,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "mm/ioremap.c:152",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503825732,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236446988,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
int ioremap_pud_range(pgd_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297670896,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297670896,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279720184,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589652592,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652592,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589378400,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589378400,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590095968,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590095968,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```

```json
{
  "name": "ioremap_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590146224,
      "name": "ioremap_pud_range",
      "external": false,
      "loc": "lib/ioremap.c:146",
      "file": "lib/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ioremap.c:ioremap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590146224,
      "name": "ioremap_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1067
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgtbl_mod_mask * mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot, pgtbl_mod_mask * mask)
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
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ioremap_pud_range(p4d_t * p4d, long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot)
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
