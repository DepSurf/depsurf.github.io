# Function: <code>blk_mq_in_flight</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417808,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:113",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417808,
      "name": "blk_mq_in_flight",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_mq_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628960,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:109",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628960,
      "name": "blk_mq_in_flight",
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733680,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:111",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733680,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921680,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:113",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921680,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024976,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024976,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422784,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:112",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422784,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537776,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:115",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537776,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569232,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:115",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569232,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980016,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:115",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980016,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585691040,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:144",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691040,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586470064,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:144",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470064,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718272,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:103",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718272,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct block_device * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586989536,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:103",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989536,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495856968,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495856968,
      "name": "blk_mq_in_flight",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229204268,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229204268,
      "name": "blk_mq_in_flight",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290053696,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290053696,
      "name": "blk_mq_in_flight",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274984424,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274984424,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993712,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993712,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929568,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929568,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977472,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977472,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
unsigned int blk_mq_in_flight(struct request_queue * q, struct hd_struct * part)
```

```json
{
  "name": "blk_mq_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079712,
      "name": "blk_mq_in_flight",
      "external": true,
      "loc": "block/blk-mq.c:114",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079712,
      "name": "blk_mq_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void blk_mq_in_flight(struct request_queue * q, struct hd_struct * part, unsigned int * inflight)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int * inflight</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
