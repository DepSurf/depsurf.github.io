# Function: <code>efi_memmap_entry_valid</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595482697,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:217",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596403768,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:218",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602728285,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:219",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602900569,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:219",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698100,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:218",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604798206,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:220",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604823968,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:243",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609162252,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:258",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609162252,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 284
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612232823,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:260",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612232823,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 284
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614373470,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:260",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614373470,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 284
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615305580,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:260",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615305580,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 310
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617086529,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:263",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617086529,
      "name": "efi_memmap_entry_valid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627744400,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:242",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627744400,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619503840,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:245",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619503840,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
```

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621800672,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:245",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621800672,
      "name": "efi_memmap_entry_valid",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604737848,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:243",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604705469,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:243",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604815415,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:243",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
  "name": "efi_memmap_entry_valid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604828125,
      "name": "efi_memmap_entry_valid",
      "external": false,
      "loc": "arch/x86/platform/efi/efi.c:243",
      "file": "arch/x86/platform/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi.c:efi_clean_memmap"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t * md, int i)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
