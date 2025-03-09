# Function: <code>bt_tags_for_each</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bt_tags_for_each(struct blk_mq_tags * tags, struct blk_mq_bitmap_tags * bt, unsigned int off, busy_tag_iter_fn * fn, void * data, bool reserved)
```

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805328,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:444",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_all_tag_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805328,
      "name": "bt_tags_for_each",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void bt_tags_for_each(struct blk_mq_tags * tags, struct blk_mq_bitmap_tags * bt, unsigned int off, busy_tag_iter_fn * fn, void * data, bool reserved)
```

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583084368,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:444",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583084368,
      "name": "bt_tags_for_each",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583194208,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:270",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583250450,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:257",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583429693,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:267",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583640845,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:283",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583747107,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:310",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583936314,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:303",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584039674,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584436632,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:339",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584553039,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:299",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584585853,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:322",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584998487,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:323",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585710940,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:379",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586491132,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:373",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586738659,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:380",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587010755,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:380",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_all_tag_iter",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495873876,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229219920,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290074900,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274997508,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584008410,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583944234,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583992170,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bt_tags_for_each",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584094474,
      "name": "bt_tags_for_each",
      "external": false,
      "loc": "block/blk-mq-tag.c:304",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter",
        "block/blk-mq-tag.c:blk_mq_tagset_busy_iter"
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void bt_tags_for_each(struct blk_mq_tags * tags, struct blk_mq_bitmap_tags * bt, unsigned int off, busy_tag_iter_fn * fn, void * data, bool reserved)
```
</details>
</li>
</ul>
