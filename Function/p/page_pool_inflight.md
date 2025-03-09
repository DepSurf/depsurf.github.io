# Function: <code>page_pool_inflight</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588495605,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:199",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_safe_to_destroy"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588705848,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
s32 page_pool_inflight(struct page_pool * pool)
```

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589570464,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:265",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570464,
      "name": "page_pool_inflight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
s32 page_pool_inflight(struct page_pool * pool)
```

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589579888,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:267",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589579888,
      "name": "page_pool_inflight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589477867,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:306",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590216851,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:330",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591793404,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:450",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593587328,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:451",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594060352,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:476",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
s32 page_pool_inflight(const struct page_pool * pool, bool strict)
```

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594854752,
      "name": "page_pool_inflight",
      "external": true,
      "loc": "net/core/page_pool.c:532",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool_user.c:page_pool_nl_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594854752,
      "name": "page_pool_inflight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502266832,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235009212,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295763708,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278502668,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588312584,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588025368,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588644408,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
  "name": "page_pool_inflight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588783976,
      "name": "page_pool_inflight",
      "external": false,
      "loc": "net/core/page_pool.c:195",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
s32 page_pool_inflight(struct page_pool * pool)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
s32 page_pool_inflight(struct page_pool * pool)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
s32 page_pool_inflight(const struct page_pool * pool, bool strict)
```
</details>
</li>
</ul>
