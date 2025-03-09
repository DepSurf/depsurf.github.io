# Function: <code>crb_map_res</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585529120,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:444",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529120,
      "name": "crb_map_res.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585653616,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:454",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585653616,
      "name": "crb_map_res.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585878048,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878048,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586020608,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020608,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586758800,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586758800,
      "name": "crb_map_res",
      "section": ".text",
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
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586850336,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850336,
      "name": "crb_map_res",
      "section": ".text",
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
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730784,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730784,
      "name": "crb_map_res",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587282512,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282512,
      "name": "crb_map_res",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588594704,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594704,
      "name": "crb_map_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053296,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:456",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053296,
      "name": "crb_map_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590368829,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590363904,
      "name": "crb_map_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
```

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590710342,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:502",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705424,
      "name": "crb_map_res",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498819136,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498819136,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
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
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585781584,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781584,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585640768,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640768,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585970624,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970624,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crb_map_res",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078352,
      "name": "crb_map_res",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:450",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_map_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078352,
      "name": "crb_map_res.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * crb_map_res(struct device * dev, struct resource * iores, void * * iobase_ptr, u64 start, u32 size)
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
