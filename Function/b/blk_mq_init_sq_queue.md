# Function: <code>blk_mq_init_sq_queue</code>

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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745728,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2657",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745728,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583934688,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2703",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934688,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584038048,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038048,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432784,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2926",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432784,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549280,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:3031",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549280,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581888,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:3091",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581888,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495871280,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495871280,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229218432,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229218432,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290072512,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290072512,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274996126,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274996126,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584006784,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006784,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942608,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942608,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583990544,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990544,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
```

```json
{
  "name": "blk_mq_init_sq_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584092848,
      "name": "blk_mq_init_sq_queue",
      "external": true,
      "loc": "block/blk-mq.c:2726",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092848,
      "name": "blk_mq_init_sq_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct request_queue * blk_mq_init_sq_queue(struct blk_mq_tag_set * set, const struct blk_mq_ops * ops, unsigned int queue_depth, unsigned int set_flags)
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
