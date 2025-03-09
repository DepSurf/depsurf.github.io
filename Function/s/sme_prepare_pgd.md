# Function: <code>sme_prepare_pgd</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
pmd_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602723426,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:515",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602723426,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 219
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602897175,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:94",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602897175,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604694559,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:95",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604694559,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604794581,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604794581,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604820304,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604820304,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609158586,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609158586,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 309
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612229184,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612229184,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 309
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614369940,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614369940,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 307
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615301875,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:114",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615301875,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 350
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617082141,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617082141,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 364
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627737168,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627737168,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 564
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619496384,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619496384,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 466
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621793216,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:117",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621793216,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 466
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604734184,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604734184,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604701805,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604701805,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604811751,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604811751,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_prepare_pgd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604824461,
      "name": "sme_prepare_pgd",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:105",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604824461,
      "name": "sme_prepare_pgd",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
pmd_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>pmd_t *</code> ➡️ <code>pud_t *</code>
</li>
</ul>
</details>
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
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pud_t * sme_prepare_pgd(struct sme_populate_pgd_data * ppd)
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
