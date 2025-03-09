# Function: <code>bio_crypt_ctx_mergeable</code>

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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619152,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:183",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_merge_requests_fn",
        "block/blk-merge.c:ll_front_merge_fn",
        "block/blk-merge.c:ll_back_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619152,
      "name": "bio_crypt_ctx_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737920,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:194",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:ll_merge_requests_fn",
        "block/blk-merge.c:ll_front_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737920,
      "name": "bio_crypt_ctx_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584766032,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:194",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584766032,
      "name": "bio_crypt_ctx_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194832,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:194",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194832,
      "name": "bio_crypt_ctx_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929648,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:196",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_back_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929648,
      "name": "bio_crypt_ctx_mergeable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720624,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:202",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_back_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720624,
      "name": "bio_crypt_ctx_mergeable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586983248,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:203",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_back_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983248,
      "name": "bio_crypt_ctx_mergeable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
```

```json
{
  "name": "bio_crypt_ctx_mergeable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264992,
      "name": "bio_crypt_ctx_mergeable",
      "external": true,
      "loc": "block/blk-crypto.c:203",
      "file": "block/blk-crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:bio_attempt_front_merge",
        "block/blk-merge.c:attempt_merge",
        "block/blk-merge.c:ll_back_merge_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264992,
      "name": "bio_crypt_ctx_mergeable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool bio_crypt_ctx_mergeable(struct bio_crypt_ctx * bc1, unsigned int bc1_bytes, struct bio_crypt_ctx * bc2)
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
