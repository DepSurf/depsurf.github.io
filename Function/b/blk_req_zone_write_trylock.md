# Function: <code>blk_req_zone_write_trylock</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584582112,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:85",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582112,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584699792,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:85",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699792,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584727520,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:77",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584727520,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585155143,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:77",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592321928,
      "name": "blk_req_zone_write_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585155088,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585890247,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:76",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106725,
      "name": "blk_req_zone_write_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585890192,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:73",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110594,
      "name": "blk_req_zone_write_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586678160,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:67",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596634988,
      "name": "blk_req_zone_write_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586939440,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
```

```json
{
  "name": "blk_req_zone_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_req_zone_write_trylock",
      "external": true,
      "loc": "block/blk-zoned.c:67",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597542387,
      "name": "blk_req_zone_write_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071587220192,
      "name": "blk_req_zone_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool blk_req_zone_write_trylock(struct request * rq)
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
