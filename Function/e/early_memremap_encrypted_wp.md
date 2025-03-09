# Function: <code>early_memremap_encrypted_wp</code>

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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602713902,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:712",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602713902,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602886549,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:712",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602886549,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604683559,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:720",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604683559,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604783074,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:745",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604783074,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604808841,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604808841,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609147466,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:778",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609147466,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612217808,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:778",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612217808,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614358987,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:761",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614358987,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615289511,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:806",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615289511,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617068918,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:811",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617068918,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627717664,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:820",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627717664,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619475136,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:825",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619475136,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621771616,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:825",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621771616,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604722783,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604722783,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604690642,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604690642,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604800350,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604800350,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap_encrypted_wp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604812969,
      "name": "early_memremap_encrypted_wp",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:767",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604812969,
      "name": "early_memremap_encrypted_wp",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
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
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size)
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
