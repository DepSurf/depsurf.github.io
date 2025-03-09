# Function: <code>bio_iov_bvec_set</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584499937,
      "name": "bio_iov_bvec_set",
      "external": false,
      "loc": "block/bio.c:964",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584910564,
      "name": "bio_iov_bvec_set",
      "external": false,
      "loc": "block/bio.c:1047",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585610144,
      "name": "bio_iov_bvec_set",
      "external": true,
      "loc": "block/bio.c:1133",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_iov_iter_get_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610144,
      "name": "bio_iov_bvec_set",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380096,
      "name": "bio_iov_bvec_set",
      "external": true,
      "loc": "block/bio.c:1185",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380096,
      "name": "bio_iov_bvec_set",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626400,
      "name": "bio_iov_bvec_set",
      "external": true,
      "loc": "block/bio.c:1161",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626400,
      "name": "bio_iov_bvec_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void bio_iov_bvec_set(struct bio * bio, struct iov_iter * iter)
```

```json
{
  "name": "bio_iov_bvec_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586897920,
      "name": "bio_iov_bvec_set",
      "external": true,
      "loc": "block/bio.c:1171",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/fops.c:__blkdev_direct_IO_async",
        "block/bio.c:bio_iov_iter_get_pages",
        "block/blk-map.c:blk_rq_map_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586897920,
      "name": "bio_iov_bvec_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void bio_iov_bvec_set(struct bio * bio, struct iov_iter * iter)
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
