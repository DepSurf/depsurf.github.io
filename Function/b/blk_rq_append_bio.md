# Function: <code>blk_rq_append_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request_queue * q, struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775040,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:30",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_make_request",
        "block/blk-map.c:blk_rq_map_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775040,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583052672,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:16",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052672,
      "name": "blk_rq_append_bio",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583158448,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:16",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158448,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215760,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:17",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215760,
      "name": "blk_rq_append_bio",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583392544,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392544,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583602544,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602544,
      "name": "blk_rq_append_bio",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583708592,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708592,
      "name": "blk_rq_append_bio",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897056,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897056,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000400,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000400,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584390336,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:527",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584390336,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503648,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:524",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503648,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538048,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:482",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538048,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949168,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:482",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949168,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585652928,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:490",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585652928,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426192,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:531",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426192,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586673648,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:530",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586673648,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int blk_rq_append_bio(struct request * rq, struct bio * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944528,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:537",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_map_user_iov",
        "block/blk-map.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944528,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495829744,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495829744,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229177740,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229177740,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290019328,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290019328,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274962910,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274962910,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969136,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov",
        "drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969136,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583906032,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583906032,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952896,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952896,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int blk_rq_append_bio(struct request * rq, struct bio * * bio)
```

```json
{
  "name": "blk_rq_append_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584054896,
      "name": "blk_rq_append_bio",
      "external": true,
      "loc": "block/blk-map.c:18",
      "file": "block/blk-map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054896,
      "name": "blk_rq_append_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rq, bio</code> ➡️ <code>rq, bio</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bio * bio</code> ➡️ <code>struct bio * * bio</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bio * * bio</code> ➡️ <code>struct bio * bio</code>
</li>
</ul>
</details>
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
