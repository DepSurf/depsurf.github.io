# Function: <code>__generic_fsdax_supported</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586444624,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444624,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071586445840,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592560,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592560,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071586593776,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587378640,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378640,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1298
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
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587439360,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:70",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439360,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587320048,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:70",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587320048,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499475472,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499475472,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231948804,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231948804,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292755168,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292755168,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
    },
    {
      "addr": 13835058055292756672,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276695820,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276695820,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586283040,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586283040,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071586284256,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586120528,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/pmem.c:generic_fsdax_supported",
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120528,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071586121744,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586540528,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586540528,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071586541744,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```

```json
{
  "name": "__generic_fsdax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586652240,
      "name": "__generic_fsdax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:69",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652240,
      "name": "__generic_fsdax_supported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1266
    },
    {
      "addr": 18446744071586653520,
      "name": "__generic_fsdax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool __generic_fsdax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t sectors)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
