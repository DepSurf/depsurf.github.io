# Function: <code>bvec_split_segs</code>

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
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583899072,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:164",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899072,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002304,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002304,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395008,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:196",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:blk_bio_segment_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395008,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509072,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:197",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:blk_bio_segment_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509072,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543184,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:197",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:blk_bio_segment_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543184,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584954480,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:197",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:blk_bio_segment_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954480,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585658464,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:217",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:blk_bio_segment_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658464,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
bool bvec_split_segs(const struct queue_limits * lim, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * bytes, unsigned int max_segs, unsigned int max_bytes)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586433408,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:231",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:bio_split_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433408,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool bvec_split_segs(const struct queue_limits * lim, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * bytes, unsigned int max_segs, unsigned int max_bytes)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586680576,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:231",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:bio_split_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586680576,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool bvec_split_segs(const struct queue_limits * lim, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * bytes, unsigned int max_segs, unsigned int max_bytes)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951888,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:227",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:bio_split_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951888,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495831944,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495831944,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229179852,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229179852,
      "name": "bvec_split_segs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290022256,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290022256,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274964562,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274964562,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583971040,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971040,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583907936,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907936,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583954800,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954800,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bvec_split_segs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584056784,
      "name": "bvec_split_segs",
      "external": false,
      "loc": "block/blk-merge.c:193",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_recalc_rq_segments",
        "block/blk-merge.c:__blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056784,
      "name": "bvec_split_segs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct queue_limits * lim</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int * bytes</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int max_bytes</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * sectors</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int max_sectors</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool bvec_split_segs(const struct request_queue * q, const struct bio_vec * bv, unsigned int * nsegs, unsigned int * sectors, unsigned int max_segs, unsigned int max_sectors)
```
</details>
</li>
</ul>
