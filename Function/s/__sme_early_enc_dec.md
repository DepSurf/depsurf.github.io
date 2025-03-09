# Function: <code>__sme_early_enc_dec</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602724293,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:63",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602723785,
      "name": "__sme_early_enc_dec.part.6",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 192
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602895517,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:58",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602895517,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 205
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604692826,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:58",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604692826,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 205
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604792831,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604792831,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604818552,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604818552,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609156684,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609156684,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612227179,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:61",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612227179,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614367965,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:60",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614367965,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 206
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615299515,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:61",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615299515,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 206
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617079672,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:91",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt_amd.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617079672,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627733744,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:92",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627733744,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 563
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619492992,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:92",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619492992,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 571
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621789952,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:91",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc",
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621789952,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 571
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732432,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732432,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604700157,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604700157,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604809999,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604809999,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```

```json
{
  "name": "__sme_early_enc_dec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604822709,
      "name": "__sme_early_enc_dec",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_early_decrypt",
        "arch/x86/mm/mem_encrypt.c:sme_early_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604822709,
      "name": "__sme_early_enc_dec",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 212
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc)
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
