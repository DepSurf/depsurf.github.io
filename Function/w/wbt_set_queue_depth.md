# Function: <code>wbt_set_queue_depth</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void wbt_set_queue_depth(struct rq_wb * rwb, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345776,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:655",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345776,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_set_queue_depth(struct rq_wb * rwb, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583404205,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:642",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_init"
      ],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403760,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_set_queue_depth(struct rq_wb * rwb, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583583743,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:641",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_init"
      ],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583312,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbt_set_queue_depth(struct rq_wb * rwb, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583800555,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:674",
      "file": "block/blk-wbt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_init"
      ],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800080,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void wbt_set_queue_depth(struct request_queue * q, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882272,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:631",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882272,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wbt_set_queue_depth(struct request_queue * q, unsigned int depth)
```

```json
{
  "name": "wbt_set_queue_depth",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072896,
      "name": "wbt_set_queue_depth",
      "external": true,
      "loc": "block/blk-wbt.c:632",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-settings.c:blk_set_queue_depth",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072896,
      "name": "wbt_set_queue_depth",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void wbt_set_queue_depth(struct rq_wb * rwb, unsigned int depth)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb * rwb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void wbt_set_queue_depth(struct request_queue * q, unsigned int depth)
```
</details>
</li>
</ul>
