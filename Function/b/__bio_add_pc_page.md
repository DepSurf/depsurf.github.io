# Function: <code>__bio_add_pc_page</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool put_same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845888,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:686",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845888,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583948240,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948240,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495768520,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495768520,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229122748,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229122748,
      "name": "__bio_add_pc_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289942528,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289942528,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274915688,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274915688,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583916976,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916976,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583853840,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853840,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583900736,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900736,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```

```json
{
  "name": "__bio_add_pc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584001888,
      "name": "__bio_add_pc_page",
      "external": false,
      "loc": "block/bio.c:733",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_map_kern",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_copy_user_iov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001888,
      "name": "__bio_add_pc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool put_same_page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * same_page</code>
</li>
<li>
<b>Param removed. </b>
<code>bool put_same_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __bio_add_pc_page(struct request_queue * q, struct bio * bio, struct page * page, unsigned int len, unsigned int offset, bool * same_page)
```
</details>
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
