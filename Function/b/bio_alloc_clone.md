# Function: <code>bio_alloc_clone</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * bio_alloc_clone(struct block_device * bdev, struct bio * bio_src, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585608706,
      "name": "bio_alloc_clone",
      "external": true,
      "loc": "block/bio.c:795",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_split"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_rq_prep_clone",
        "drivers/md/md.c:md_account_bio",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:alloc_tio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608528,
      "name": "bio_alloc_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * bio_alloc_clone(struct block_device * bdev, struct bio * bio_src, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377618,
      "name": "bio_alloc_clone",
      "external": true,
      "loc": "block/bio.c:846",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_split"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_rq_prep_clone",
        "drivers/md/md.c:md_account_bio",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-io-rewind.c:dm_io_rewind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377424,
      "name": "bio_alloc_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * bio_alloc_clone(struct block_device * bdev, struct bio * bio_src, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586623938,
      "name": "bio_alloc_clone",
      "external": true,
      "loc": "block/bio.c:845",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_split"
      ],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/blk-mq.c:blk_rq_prep_clone",
        "drivers/md/md.c:md_account_bio",
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm-io-rewind.c:dm_io_rewind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623744,
      "name": "bio_alloc_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * bio_alloc_clone(struct block_device * bdev, struct bio * bio_src, gfp_t gfp, struct bio_set * bs)
```

```json
{
  "name": "bio_alloc_clone",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586895442,
      "name": "bio_alloc_clone",
      "external": true,
      "loc": "block/bio.c:845",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_split"
      ],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_bio_read_cached",
        "block/blk-mq.c:blk_rq_prep_clone",
        "drivers/md/md.c:md_account_bio",
        "drivers/md/dm.c:alloc_tio",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-io-rewind.c:dm_io_rewind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895248,
      "name": "bio_alloc_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct bio * bio_alloc_clone(struct block_device * bdev, struct bio * bio_src, gfp_t gfp, struct bio_set * bs)
```
</details>
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
