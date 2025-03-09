# Function: <code>check_and_migrate_movable_pages</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560416,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:1635",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560416,
      "name": "check_and_migrate_movable_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825040,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:1723",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825040,
      "name": "check_and_migrate_movable_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218880,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:1904",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218880,
      "name": "check_and_migrate_movable_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708128,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:2016",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708128,
      "name": "check_and_migrate_movable_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582934787,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:2148",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_longterm_locked"
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
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages)
```

```json
{
  "name": "check_and_migrate_movable_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096816,
      "name": "check_and_migrate_movable_pages",
      "external": false,
      "loc": "mm/gup.c:2174",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096816,
      "name": "check_and_migrate_movable_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages, unsigned int gup_flags)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long int check_and_migrate_movable_pages(long unsigned int nr_pages, struct page * * pages)
```
</details>
</li>
</ul>
