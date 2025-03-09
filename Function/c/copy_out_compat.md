# Function: <code>copy_out_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586000219,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586407500,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586616734,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738288,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738288,
      "name": "copy_out_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587222784,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587222784,
      "name": "copy_out_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587523872,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:241",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523872,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704704,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:233",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704704,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983728,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:177",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983728,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190928,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190928,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589057008,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057008,
      "name": "copy_out_compat",
      "section": ".text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589064496,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:184",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589064496,
      "name": "copy_out_compat",
      "section": ".text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588951600,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:184",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588951600,
      "name": "copy_out_compat",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660880,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:184",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660880,
      "name": "copy_out_compat",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163840,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:184",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163840,
      "name": "copy_out_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501546512,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501546512,
      "name": "copy_out_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587809360,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809360,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587512784,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512784,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145456,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145456,
      "name": "copy_out_compat",
      "section": ".text",
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
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```

```json
{
  "name": "copy_out_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262864,
      "name": "copy_out_compat",
      "external": false,
      "loc": "drivers/firmware/efi/efivars.c:186",
      "file": "drivers/firmware/efi/efivars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efivars.c:efivar_create",
        "drivers/firmware/efi/efivars.c:efivar_store_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262864,
      "name": "copy_out_compat",
      "section": ".text",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void copy_out_compat(struct efi_variable * dst, struct compat_efi_variable * src)
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
