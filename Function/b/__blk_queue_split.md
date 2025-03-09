# Function: <code>__blk_queue_split</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901088,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:253",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901088,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1254
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004384,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004384,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584398928,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:297",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398928,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void __blk_queue_split(struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584514512,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:306",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514512,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void __blk_queue_split(struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584546704,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:305",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546704,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
void __blk_queue_split(struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584958000,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:305",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958000,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662016,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:325",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662016,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495833920,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495833920,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229182260,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229182260,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290024704,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290024704,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274966286,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274966286,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583973120,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973120,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909856,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909856,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956880,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956880,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
```

```json
{
  "name": "__blk_queue_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584058864,
      "name": "__blk_queue_split",
      "external": true,
      "loc": "block/blk-merge.c:293",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584058864,
      "name": "__blk_queue_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1171
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
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio, nr_segs</code> ➡️ <code>bio, nr_segs</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, nr_segs</code> ➡️ <code>q, bio, nr_segs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __blk_queue_split(struct request_queue * q, struct bio * * bio, unsigned int * nr_segs)
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
