# Function: <code>blk_mq_submit_bio</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
blk_qc_t blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584542048,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2129",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542048,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1389
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
blk_qc_t blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573760,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2153",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573760,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1402
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
blk_qc_t blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2176",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592314154,
      "name": "blk_mq_submit_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584986608,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1525
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
void blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585699600,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2800",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699600,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1127
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
void blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586479040,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2955",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586479040,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1284
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
void blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586726512,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2962",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726512,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1387
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
void blk_mq_submit_bio(struct bio * bio)
```

```json
{
  "name": "blk_mq_submit_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_submit_bio",
      "external": true,
      "loc": "block/blk-mq.c:2959",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597536917,
      "name": "blk_mq_submit_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586997632,
      "name": "blk_mq_submit_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1893
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
blk_qc_t blk_mq_submit_bio(struct bio * bio)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
</li>
</ul>
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
