# Function: <code>internal_get_user_pages_fast</code>

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
int internal_get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512560,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2739",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512560,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552960,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2564",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552960,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575952,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2630",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575952,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840576,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2725",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840576,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232944,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2875",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232944,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723536,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:2900",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast_only",
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723536,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939712,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:3159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939712,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int internal_get_user_pages_fast(long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages)
```

```json
{
  "name": "internal_get_user_pages_fast",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114928,
      "name": "internal_get_user_pages_fast",
      "external": false,
      "loc": "mm/gup.c:3177",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:pin_user_pages_fast",
        "mm/gup.c:get_user_pages_fast",
        "mm/gup.c:get_user_pages_fast_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114928,
      "name": "internal_get_user_pages_fast",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int internal_get_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>long unsigned int nr_pages</code>
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
