# Function: <code>__early_make_pgtable</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602582217,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:188",
      "file": "arch/x86/kernel/head64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602582217,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602750150,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:264",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602750150,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604544209,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:280",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604544209,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604638318,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:282",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604638318,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604650606,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604650606,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609000558,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609000558,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 631
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612064430,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:322",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612064430,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614202542,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:322",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614202542,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 629
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615120046,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:322",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615120046,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 751
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616881328,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:331",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616881328,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 788
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627469648,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:331",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627469648,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 943
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619298688,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:331",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619298688,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 968
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
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621592176,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:330",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:do_early_exception",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621592176,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604576878,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604576878,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604568598,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604568598,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604654702,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604654702,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```

```json
{
  "name": "__early_make_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604654702,
      "name": "__early_make_pgtable",
      "external": true,
      "loc": "arch/x86/kernel/head64.c:300",
      "file": "arch/x86/kernel/head64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:early_make_pgtable",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604654702,
      "name": "__early_make_pgtable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 440
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd)
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
