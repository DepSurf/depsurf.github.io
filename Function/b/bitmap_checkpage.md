# Function: <code>bitmap_checkpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585777758,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/bitmap.c:48",
      "file": "drivers/md/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_get_counter"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586175488,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/bitmap.c:48",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_get_counter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586175488,
      "name": "bitmap_checkpage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379360,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/bitmap.c:49",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_get_counter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379360,
      "name": "bitmap_checkpage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586482976,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/bitmap.c:49",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_get_counter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482976,
      "name": "bitmap_checkpage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950656,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:49",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_get_counter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950656,
      "name": "bitmap_checkpage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```

```json
{
  "name": "bitmap_checkpage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245968,
      "name": "bitmap_checkpage",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:49",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_get_counter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245968,
      "name": "bitmap_checkpage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
int bitmap_checkpage(struct bitmap_counts * bitmap, long unsigned int page, int create, int no_hijack)
```
</details>
</li>
</ul>
