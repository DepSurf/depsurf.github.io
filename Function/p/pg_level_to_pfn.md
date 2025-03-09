# Function: <code>pg_level_to_pfn</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t * kpte, pgprot_t * ret_prot)
```

```json
{
  "name": "pg_level_to_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pg_level_to_pfn",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:251",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604880,
      "name": "pg_level_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071593860314,
      "name": "pg_level_to_pfn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t * kpte, pgprot_t * ret_prot)
```

```json
{
  "name": "pg_level_to_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pg_level_to_pfn",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:252",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718672,
      "name": "pg_level_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071595971595,
      "name": "pg_level_to_pfn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t * kpte, pgprot_t * ret_prot)
```

```json
{
  "name": "pg_level_to_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pg_level_to_pfn",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:252",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732336,
      "name": "pg_level_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071596489174,
      "name": "pg_level_to_pfn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t * kpte, pgprot_t * ret_prot)
```

```json
{
  "name": "pg_level_to_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pg_level_to_pfn",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:217",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767280,
      "name": "pg_level_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071597385796,
      "name": "pg_level_to_pfn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t * kpte, pgprot_t * ret_prot)
```
</details>
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
