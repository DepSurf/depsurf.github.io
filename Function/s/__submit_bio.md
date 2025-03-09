# Function: <code>__submit_bio</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584486778,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:927",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct"
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
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584521430,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:913",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
blk_qc_t __submit_bio(struct bio * bio)
```

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584928752,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:909",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584928752,
      "name": "__submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
void __submit_bio(struct bio * bio)
```

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630976,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:640",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630976,
      "name": "__submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void __submit_bio(struct bio * bio)
```

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586402192,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:594",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:submit_bio_noacct_nocheck",
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402192,
      "name": "__submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void __submit_bio(struct bio * bio)
```

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:592",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:submit_bio_noacct_nocheck",
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649328,
      "name": "__submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071596628661,
      "name": "__submit_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __submit_bio(struct bio * bio)
```

```json
{
  "name": "__submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__submit_bio",
      "external": false,
      "loc": "block/blk-core.c:602",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:submit_bio_noacct_nocheck",
        "block/blk-core.c:__submit_bio_noacct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920496,
      "name": "__submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071597534880,
      "name": "__submit_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
blk_qc_t __submit_bio(struct bio * bio)
```
</details>
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
