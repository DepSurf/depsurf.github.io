# Function: <code>blk_mq_all_tag_iter</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436336,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:376",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436336,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552736,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:336",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552736,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585552,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:359",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585552,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:360",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592314546,
      "name": "blk_mq_all_tag_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071584999968,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:416",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594098382,
      "name": "blk_mq_all_tag_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071585713328,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:410",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596106912,
      "name": "blk_mq_all_tag_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071586493664,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:417",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596630818,
      "name": "blk_mq_all_tag_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071586741248,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
```

```json
{
  "name": "blk_mq_all_tag_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_all_tag_iter",
      "external": true,
      "loc": "block/blk-mq-tag.c:417",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597537351,
      "name": "blk_mq_all_tag_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071587013328,
      "name": "blk_mq_all_tag_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags * tags, busy_tag_iter_fn * fn, void * priv)
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
