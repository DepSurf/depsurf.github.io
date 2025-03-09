# Function: <code>zero_fill_bio_iter</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538512,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:533",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538512,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660896,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:535",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660896,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847664,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:523",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847664,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950720,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950720,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342128,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:530",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342128,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459968,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:532",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459968,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586889376,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:609",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_read_simple",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586889376,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495770376,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495770376,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229124080,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229124080,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289944608,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289944608,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274917476,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274917476,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919456,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919456,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583856416,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856416,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903216,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903216,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```

```json
{
  "name": "zero_fill_bio_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004368,
      "name": "zero_fill_bio_iter",
      "external": true,
      "loc": "block/bio.c:526",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_user_iov",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/md/dm-io.c:endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004368,
      "name": "zero_fill_bio_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```
</details>
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
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void zero_fill_bio_iter(struct bio * bio, struct bvec_iter start)
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
