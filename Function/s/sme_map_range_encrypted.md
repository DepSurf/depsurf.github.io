# Function: <code>sme_map_range_encrypted</code>

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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602724195,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt.c:671",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602724195,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602898268,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:217",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604695652,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:218",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604795706,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604821438,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609159278,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609159278,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612229876,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612229876,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614370622,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614370622,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615302600,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:237",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615302600,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 29
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
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617082893,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:240",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617082893,
      "name": "sme_map_range_encrypted",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 39
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627738931,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:240",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619498048,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:240",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621794880,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:240",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604735318,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604702939,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604812885,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
  "name": "sme_map_range_encrypted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604825595,
      "name": "sme_map_range_encrypted",
      "external": false,
      "loc": "arch/x86/mm/mem_encrypt_identity.c:228",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data * ppd)
```
</details>
</li>
</ul>
