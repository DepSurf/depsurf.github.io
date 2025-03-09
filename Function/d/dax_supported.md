# Function: <code>dax_supported</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586444417,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445968,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592353,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593904,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378433,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376512,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587439150,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:326",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:device_not_dax_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437200,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321870,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:326",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:device_not_dax_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318976,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887200,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:205",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "drivers/md/dm-table.c:device_not_dax_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887200,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499475248,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499477288,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231950688,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231951016,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292754792,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292756896,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276695630,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276696474,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282833,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284384,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586120321,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586121872,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586540321,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541872,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
```

```json
{
  "name": "dax_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586652033,
      "name": "dax_supported",
      "external": true,
      "loc": "drivers/dax/super.c:318",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653648,
      "name": "dax_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool dax_supported(struct dax_device * dax_dev, struct block_device * bdev, int blocksize, sector_t start, sector_t len)
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
