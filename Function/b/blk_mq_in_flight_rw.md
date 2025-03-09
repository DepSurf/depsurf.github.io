# Function: <code>blk_mq_in_flight_rw</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629056,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:128",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629056,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733776,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:134",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733776,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921776,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:136",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921776,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025072,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025072,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422880,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:121",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422880,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537872,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:125",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537872,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569328,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:125",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569328,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980112,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:125",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980112,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691136,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:154",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691136,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586470176,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:154",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470176,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718384,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:113",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718384,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct block_device * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586989648,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:113",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_inflight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989648,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495857088,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495857088,
      "name": "blk_mq_in_flight_rw",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229204396,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229204396,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290053840,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290053840,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274984504,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274984504,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993808,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993808,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929664,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929664,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977568,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977568,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079808,
      "name": "blk_mq_in_flight_rw",
      "external": true,
      "loc": "block/blk-mq.c:137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:part_in_flight_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079808,
      "name": "blk_mq_in_flight_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void blk_mq_in_flight_rw(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hd_struct * part</code> ➡️ <code>struct block_device * part</code>
</li>
</ul>
</details>
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
