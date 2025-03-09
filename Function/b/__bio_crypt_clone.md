# Function: <code>__bio_crypt_clone</code>

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
void __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618384,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:98",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618384,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737392,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:106",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:clone_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737392,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584765424,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:106",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765424,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194176,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:106",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_fast",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194176,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929168,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:109",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929168,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720064,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:115",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720064,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982592,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:116",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982592,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```

```json
{
  "name": "__bio_crypt_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264336,
      "name": "__bio_crypt_clone",
      "external": true,
      "loc": "block/blk-crypto.c:116",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bio_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264336,
      "name": "__bio_crypt_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __bio_crypt_clone(struct bio * dst, struct bio * src, gfp_t gfp_mask)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
