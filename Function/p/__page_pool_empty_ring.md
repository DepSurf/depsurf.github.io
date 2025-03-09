# Function: <code>__page_pool_empty_ring</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __page_pool_empty_ring(struct page_pool * pool)
```

```json
{
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:267",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_destroy",
        "net/core/page_pool.c:__page_pool_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010624,
      "name": "__page_pool_empty_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071588012059,
      "name": "__page_pool_empty_ring.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __page_pool_empty_ring(struct page_pool * pool)
```

```json
{
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:267",
      "file": "net/core/page_pool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/page_pool.c:page_pool_destroy",
        "net/core/page_pool.c:__page_pool_destroy_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171360,
      "name": "__page_pool_empty_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071588172795,
      "name": "__page_pool_empty_ring.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:333",
      "file": "net/core/page_pool.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_request_shutdown"
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278502486,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
  "name": "__page_pool_empty_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__page_pool_empty_ring",
      "external": false,
      "loc": "net/core/page_pool.c:324",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __page_pool_empty_ring(struct page_pool * pool)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __page_pool_empty_ring(struct page_pool * pool)
```
</details>
</li>
</ul>
