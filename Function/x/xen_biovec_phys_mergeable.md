# Function: <code>xen_biovec_phys_mergeable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901616,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:6",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:attempt_merge",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901616,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232672,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:6",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232672,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584414144,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:6",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414144,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584497904,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:6",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584497904,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584907840,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:7",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907840,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585139376,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:7",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139376,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct bio_vec * vec2)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585250176,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:7",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_recalc_rq_segments",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250176,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462272,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/bio.c:__bio_add_pc_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462272,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602992,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602992,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586325632,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586325632,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443488,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_merge_requests_fn",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443488,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586327344,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327344,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847104,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847104,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588133296,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588133296,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522160,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522160,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589823152,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bvec_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589823152,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590159824,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bvec_try_merge_page",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:bio_will_gap",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159824,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498268544,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498268544,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585365616,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365616,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585553392,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585553392,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```

```json
{
  "name": "xen_biovec_phys_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661344,
      "name": "xen_biovec_phys_mergeable",
      "external": true,
      "loc": "drivers/xen/biomerge.c:8",
      "file": "drivers/xen/biomerge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_try_merge_page",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "block/blk-integrity.c:blk_rq_count_integrity_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661344,
      "name": "xen_biovec_phys_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct page * page</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct bio_vec * vec2</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool xen_biovec_phys_mergeable(const struct bio_vec * vec1, const struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
