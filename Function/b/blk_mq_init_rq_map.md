# Function: <code>blk_mq_init_rq_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_tags * blk_mq_init_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_init_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792448,
      "name": "blk_mq_init_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1454",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792448,
      "name": "blk_mq_init_rq_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
struct blk_mq_tags * blk_mq_init_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_init_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071856,
      "name": "blk_mq_init_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1520",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071856,
      "name": "blk_mq_init_rq_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
struct blk_mq_tags * blk_mq_init_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_init_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181584,
      "name": "blk_mq_init_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1582",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181584,
      "name": "blk_mq_init_rq_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct blk_mq_tags * blk_mq_init_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx)
```
</details>
</li>
</ul>
