# Function: <code>bio_clone_blkg_association</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583662688,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2098",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662528,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850717,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2132",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850560,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583950048,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949888,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584342016,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:1753",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340480,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584635440,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:1884",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone_fast",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635440,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662528,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:1893",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone_fast",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662528,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077808,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:1887",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone_fast",
        "block/blk-crypto-fallback.c:blk_crypto_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077808,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808064,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:1975",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808064,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589712,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:1981",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589712,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846944,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:2072",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846944,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587124256,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/blk-cgroup.c:2088",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "block/bio.c:__bio_clone",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio",
        "drivers/md/md.c:md_submit_discard_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124256,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495774012,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495773816,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229123808,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229123624,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289944188,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289943936,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274916700,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274916530,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583918784,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918624,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855744,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855584,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902544,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_clone_fast"
      ],
      "caller_func": [
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902384,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```

```json
{
  "name": "bio_clone_blkg_association",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003616,
      "name": "bio_clone_blkg_association",
      "external": true,
      "loc": "block/bio.c:2174",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone_fast",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003616,
      "name": "bio_clone_blkg_association",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bio_clone_blkg_association(struct bio * dst, struct bio * src)
```
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
