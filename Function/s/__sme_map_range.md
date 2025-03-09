# Function: <code>__sme_map_range</code>

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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602723977,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:647",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_map_range_decrypted_wp",
        "arch/x86/mm/mem_encrypt.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt.c:sme_map_range_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602723977,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 218
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602897616,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:193",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602897616,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 230
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604695000,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604695000,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 230
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604795022,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604795022,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604820749,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604820749,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609159109,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609159109,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 169
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612229707,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612229707,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 169
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614370457,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614370457,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 165
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615302435,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:213",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615302435,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 165
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617082721,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:216",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617082721,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 172
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627738048,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:216",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627738048,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619497168,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:216",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619497168,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621794000,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:216",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621794000,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604734629,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604734629,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604702250,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604702250,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604812196,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604812196,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```

```json
{
  "name": "__sme_map_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604824906,
      "name": "__sme_map_range",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:204",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604824906,
      "name": "__sme_map_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
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
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data * ppd, pmdval_t pmd_flags, pteval_t pte_flags)
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
