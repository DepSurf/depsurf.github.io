# Function: <code>bio_end_io_acct_remapped</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513408,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:1361",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513408,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924624,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:1351",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/dm.c:dm_io_dec_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924624,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635536,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:1056",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_end_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635536,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586406720,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:994",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_end_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406720,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653920,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:993",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_end_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653920,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```

```json
{
  "name": "bio_end_io_acct_remapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586925184,
      "name": "bio_end_io_acct_remapped",
      "external": true,
      "loc": "block/blk-core.c:1028",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_end_clone_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925184,
      "name": "bio_end_io_acct_remapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void bio_end_io_acct_remapped(struct bio * bio, long unsigned int start_time, struct block_device * orig_bdev)
```
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
