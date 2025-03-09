# Function: <code>blk_mq_free_map_and_rqs</code>

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
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_map_and_rqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702092,
      "name": "blk_mq_free_map_and_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3638",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707952,
      "name": "blk_mq_free_map_and_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_map_and_rqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586481772,
      "name": "blk_mq_free_map_and_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3802",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586486432,
      "name": "blk_mq_free_map_and_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_map_and_rqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586729340,
      "name": "blk_mq_free_map_and_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3814",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734032,
      "name": "blk_mq_free_map_and_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_map_and_rqs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587000972,
      "name": "blk_mq_free_map_and_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3830",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587006080,
      "name": "blk_mq_free_map_and_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
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
