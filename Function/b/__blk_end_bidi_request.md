# Function: <code>__blk_end_bidi_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __blk_end_bidi_request(struct request * rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756928,
      "name": "__blk_end_bidi_request",
      "external": true,
      "loc": "block/blk-core.c:2799",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:__blk_end_request_err",
        "block/blk-flush.c:blk_insert_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756928,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool __blk_end_bidi_request(struct request * rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034880,
      "name": "__blk_end_bidi_request",
      "external": true,
      "loc": "block/blk-core.c:2771",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request_err",
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-flush.c:blk_insert_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034880,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool __blk_end_bidi_request(struct request * rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583139888,
      "name": "__blk_end_bidi_request",
      "external": true,
      "loc": "block/blk-core.c:2768",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request_err",
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-flush.c:blk_insert_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583139888,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool __blk_end_bidi_request(struct request * rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194608,
      "name": "__blk_end_bidi_request",
      "external": false,
      "loc": "block/blk-core.c:2911",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request",
        "block/blk-core.c:__blk_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194608,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool __blk_end_bidi_request(struct request * rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371104,
      "name": "__blk_end_bidi_request",
      "external": false,
      "loc": "block/blk-core.c:3135",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request",
        "block/blk-core.c:__blk_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371104,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool __blk_end_bidi_request(struct request * rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes)
```

```json
{
  "name": "__blk_end_bidi_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583580656,
      "name": "__blk_end_bidi_request",
      "external": false,
      "loc": "block/blk-core.c:3280",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__blk_end_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580656,
      "name": "__blk_end_bidi_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
bool __blk_end_bidi_request(struct request * rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes)
```
</details>
</li>
</ul>
