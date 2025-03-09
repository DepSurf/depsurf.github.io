# Function: <code>bio_split</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719792,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1785",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719792,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001488,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1780",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001488,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105552,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1835",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105552,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161424,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1857",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161424,
      "name": "bio_split",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583332064,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1821",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332064,
      "name": "bio_split",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541216,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1878",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541216,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664896,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1811",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_queue_split",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664896,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853280,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1848",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853280,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955184,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955184,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347008,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1465",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_segment_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347008,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463744,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1468",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_segment_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463744,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498192,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1431",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_segment_split",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498192,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584908544,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1513",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_segment_split",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584908544,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608640,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1571",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_segment_split",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio",
        "drivers/md/dm.c:dm_split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608640,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586377552,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1634",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377552,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586623872,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1619",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623872,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895376,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1626",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:__bio_split_to_limits",
        "block/blk-merge.c:bio_split_rw",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895376,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495776816,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495776816,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229128876,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:blk_bio_discard_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229128876,
      "name": "bio_split",
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289951312,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289951312,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274921502,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274921502,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923920,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923920,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860864,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860864,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907680,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907680,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct bio * bio_split(struct bio * bio, int sectors, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008944,
      "name": "bio_split",
      "external": true,
      "loc": "block/bio.c:1890",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008944,
      "name": "bio_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
