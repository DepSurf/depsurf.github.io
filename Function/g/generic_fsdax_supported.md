# Function: <code>generic_fsdax_supported</code>

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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587732325,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587936597,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:123",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592523951,
      "name": "generic_fsdax_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587887376,
      "name": "generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501174872,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:156",
      "file": "drivers/md/dm-table.c",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294685452,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277879664,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587567573,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "generic_fsdax_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586098528,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587335653,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098528,
      "name": "generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587892741,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
  "name": "generic_fsdax_supported",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588008005,
      "name": "generic_fsdax_supported",
      "external": false,
      "loc": "include/linux/dax.h:124",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:device_supports_dax"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
bool generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```
</details>
</li>
</ul>
