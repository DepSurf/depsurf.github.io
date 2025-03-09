# Function: <code>bio_integrity_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582938224,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:459",
      "file": "block/bio-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bio.c:bio_clone_bioset",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582938224,
      "name": "bio_integrity_clone",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583225584,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:459",
      "file": "block/bio-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225584,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583331536,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:459",
      "file": "block/bio-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331536,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389616,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:447",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389616,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568944,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:445",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568944,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785024,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:444",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_bioset",
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785024,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865072,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:417",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865072,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056480,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056480,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178720,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178720,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573200,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:414",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573200,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584691760,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:414",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584691760,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719888,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:408",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719888,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146224,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:403",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146224,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585880048,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:404",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880048,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665472,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:404",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665472,
      "name": "bio_integrity_clone",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926848,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:416",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926848,
      "name": "bio_integrity_clone",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587207952,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:614",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587207952,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496042304,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496042304,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229372460,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229372460,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290274256,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290274256,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275120112,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275120112,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147456,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147456,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082992,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082992,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131216,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131216,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int bio_integrity_clone(struct bio * bio, struct bio * bio_src, gfp_t gfp_mask)
```

```json
{
  "name": "bio_integrity_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235312,
      "name": "bio_integrity_clone",
      "external": true,
      "loc": "block/bio-integrity.c:406",
      "file": "block/bio-integrity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235312,
      "name": "bio_integrity_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
