# Function: <code>fw_decompress_xz_pages</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586141822,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586290302,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_decompress_xz_pages(struct device * dev, struct fw_priv * fw_priv, size_t in_size, const void * in_buffer)
```

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:385",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060336,
      "name": "fw_decompress_xz_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071587062725,
      "name": "fw_decompress_xz_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_decompress_xz_pages(struct device * dev, struct fw_priv * fw_priv, size_t in_size, const void * in_buffer)
```

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:406",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144832,
      "name": "fw_decompress_xz_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071591489927,
      "name": "fw_decompress_xz_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587032139,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:407",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587599195,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:408",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588937508,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:411",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590451803,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:411",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590772043,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:411",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591114587,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:412",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499122504,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231670728,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292310544,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276438390,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586053550,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585899502,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_decompress_xz_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586349294,
      "name": "fw_decompress_xz_pages",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:380",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
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
int fw_decompress_xz_pages(struct device * dev, struct fw_priv * fw_priv, size_t in_size, const void * in_buffer)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int fw_decompress_xz_pages(struct device * dev, struct fw_priv * fw_priv, size_t in_size, const void * in_buffer)
```
</details>
</li>
</ul>
