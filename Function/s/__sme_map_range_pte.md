# Function: <code>__sme_map_range_pte</code>

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
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602724019,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:637",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt.c:__sme_map_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602897366,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:183",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602897366,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604694750,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:184",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604694750,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604794772,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604794772,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 250
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604820495,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604820495,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609159062,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609159062,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 47
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612229660,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612229660,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 47
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614370247,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614370247,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 210
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615302225,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:203",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615302225,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 210
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617082505,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:206",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617082505,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627738092,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:206",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619497212,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:206",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621794044,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:206",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604734375,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604734375,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604701996,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604701996,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604811942,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604811942,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "__sme_map_range_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604824652,
      "name": "__sme_map_range_pte",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604824652,
      "name": "__sme_map_range_pte",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
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
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data * ppd)
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
