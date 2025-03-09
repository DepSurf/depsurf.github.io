# Function: <code>blk_queue_zone_write_granularity</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533968,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:351",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_queue_set_zoned",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533968,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946976,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:354",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_set_zoned"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944928,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585650168,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:353",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_set_zoned"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647952,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586423054,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:353",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:disk_set_zoned"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420640,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586670590,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:359",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:disk_set_zoned"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_characteristics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668144,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_zone_write_granularity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586941437,
      "name": "blk_queue_zone_write_granularity",
      "external": true,
      "loc": "block/blk-settings.c:362",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:disk_set_zoned"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_read_block_characteristics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597535237,
      "name": "blk_queue_zone_write_granularity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586939456,
      "name": "blk_queue_zone_write_granularity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void blk_queue_zone_write_granularity(struct request_queue * q, unsigned int size)
```
</details>
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
