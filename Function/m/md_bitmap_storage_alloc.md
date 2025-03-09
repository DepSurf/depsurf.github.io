# Function: <code>md_bitmap_storage_alloc</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587431246,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:777",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587703459,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587907747,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
int md_bitmap_storage_alloc(struct bitmap_storage * store, long unsigned int chunks, int with_super, int slot_number)
```

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588751632,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:774",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588751632,
      "name": "md_bitmap_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int md_bitmap_storage_alloc(struct bitmap_storage * store, long unsigned int chunks, int with_super, int slot_number)
```

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772592,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:775",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772592,
      "name": "md_bitmap_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588665153,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:775",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589343194,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:775",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590816755,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:776",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592503832,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:776",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592934630,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:792",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593684446,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:809",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501137280,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233652388,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294644384,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277852566,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587538723,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587306835,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587863891,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
  "name": "md_bitmap_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587978947,
      "name": "md_bitmap_storage_alloc",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:778",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize"
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
int md_bitmap_storage_alloc(struct bitmap_storage * store, long unsigned int chunks, int with_super, int slot_number)
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
int md_bitmap_storage_alloc(struct bitmap_storage * store, long unsigned int chunks, int with_super, int slot_number)
```
</details>
</li>
</ul>
