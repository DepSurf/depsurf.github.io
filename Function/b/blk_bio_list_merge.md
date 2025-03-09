# Function: <code>blk_bio_list_merge</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519248,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1095",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519248,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584551872,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1098",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551872,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584963200,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1081",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963200,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667024,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1070",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667024,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586442672,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1139",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442672,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586689824,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1135",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586689824,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```

```json
{
  "name": "blk_bio_list_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961168,
      "name": "blk_bio_list_merge",
      "external": true,
      "loc": "block/blk-merge.c:1131",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_bio_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961168,
      "name": "blk_bio_list_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool blk_bio_list_merge(struct request_queue * q, struct list_head * list, struct bio * bio, unsigned int nr_segs)
```
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
