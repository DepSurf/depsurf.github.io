# Function: <code>bio_get_last_bvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582780408,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:318",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_back_merge_fn",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:attempt_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583060132,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:267",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054592,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583166220,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:264",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583224853,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:280",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583401573,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:276",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583610406,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:285",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583716004,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:239",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583904750,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584007966,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584401072,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:260",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509312,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:271",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_merge_requests_fn",
        "block/blk-merge.c:ll_front_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509312,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584545520,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:274",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584545520,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956816,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:273",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956816,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660784,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "block/blk-merge.c:26",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660784,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586435872,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "block/blk-merge.c:26",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586435872,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683072,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "block/blk-merge.c:26",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683072,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954384,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "block/blk-merge.c:26",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_will_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954384,
      "name": "bio_get_last_bvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495837516,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229185668,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290028892,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274968840,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583976702,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583913110,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583960462,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_get_last_bvec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584062478,
      "name": "bio_get_last_bvec",
      "external": false,
      "loc": "include/linux/bio.h:252",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bio_get_last_bvec(struct bio * bio, struct bio_vec * bv)
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
