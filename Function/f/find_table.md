# Function: <code>find_table</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247136,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071588247834,
      "name": "find_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:235",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124256,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071589125129,
      "name": "find_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:235",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589122032,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071591620695,
      "name": "find_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:244",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589011952,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071591564054,
      "name": "find_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:248",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726592,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071592684921,
      "name": "find_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:248",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235344,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071594570210,
      "name": "find_table.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592986576,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:248",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592986576,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593437584,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:248",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593437584,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594183680,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:248",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594183680,
      "name": "find_table.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501705336,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501705336,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234229444,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234229444,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295144064,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295144064,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587858832,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071587859530,
      "name": "find_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```

```json
{
  "name": "find_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_table",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_elf_loader.c:204",
      "file": "drivers/remoteproc/remoteproc_elf_loader.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_rsc_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319472,
      "name": "find_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071588320170,
      "name": "find_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct elf32_shdr * find_table(struct device * dev, struct elf32_hdr * ehdr, size_t fw_size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
