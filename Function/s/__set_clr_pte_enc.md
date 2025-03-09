# Function: <code>__set_clr_pte_enc</code>

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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602724317,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:264",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602724317,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 498
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602895751,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:198",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602895751,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604693060,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:198",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604693060,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604793072,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604793072,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 538
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604818793,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604818793,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609156989,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609156989,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 536
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612227484,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:232",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612227484,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 523
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614368264,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:231",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614368264,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 506
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615299814,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:232",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615299814,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 500
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617080105,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:347",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617080105,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 353
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627734336,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:348",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627734336,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 445
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619493584,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:349",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619493584,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621790544,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:314",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621790544,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 431
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732673,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732673,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604700393,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604700393,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 441
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604810240,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604810240,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```

```json
{
  "name": "__set_clr_pte_enc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604822950,
      "name": "__set_clr_pte_enc",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec",
        "arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604822950,
      "name": "__set_clr_pte_enc",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
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
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __set_clr_pte_enc(pte_t * kpte, int level, bool enc)
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
