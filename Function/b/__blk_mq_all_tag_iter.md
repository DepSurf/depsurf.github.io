# Function: <code>__blk_mq_all_tag_iter</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv, unsigned int flags)
```

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584434384,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:353",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434384,
      "name": "__blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv, unsigned int flags)
```

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584550912,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:313",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550912,
      "name": "__blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv, unsigned int flags)
```

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584583776,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:336",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583776,
      "name": "__blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584998152,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:337",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585710921,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:393",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586491113,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:387",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586738640,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:394",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__blk_mq_all_tag_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587010736,
      "name": "__blk_mq_all_tag_iter",
      "external": false,
      "loc": "block/blk-mq-tag.c:394",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv, unsigned int flags)
```
</details>
</li>
</ul>
