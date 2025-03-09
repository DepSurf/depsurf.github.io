# Function: <code>efivar_ssdt_load</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595506693,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:238",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595760084,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:243",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596689121,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:243",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603019152,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603191547,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:274",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
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
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605001829,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:278",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605113736,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:278",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605113736,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
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
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605153541,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605153541,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609422968,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:237",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609422968,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612496784,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:241",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612496784,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614638696,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:241",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614638696,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615596492,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:241",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615596492,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617405109,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:247",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617405109,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 401
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
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628156112,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:227",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628156112,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619923232,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:253",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619923232,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622234368,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:269",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622234368,
      "name": "efivar_ssdt_load.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 583
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511280976,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:318",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605043979,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605043979,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 413
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
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605009319,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605009319,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 413
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
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605130554,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605130554,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 413
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
int efivar_ssdt_load()
```

```json
{
  "name": "efivar_ssdt_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605157735,
      "name": "efivar_ssdt_load",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:263",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605157735,
      "name": "efivar_ssdt_load",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 413
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int efivar_ssdt_load()
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int efivar_ssdt_load()
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
int efivar_ssdt_load()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int efivar_ssdt_load()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int efivar_ssdt_load()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efivar_ssdt_load()
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
