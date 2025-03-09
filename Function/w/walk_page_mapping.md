# Function: <code>walk_page_mapping</code>

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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610560,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:515",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610560,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657952,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:515",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657952,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679584,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:515",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679584,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948864,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:563",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948864,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358240,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:563",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358240,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582860448,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:587",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582860448,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076160,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:633",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076160,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258208,
      "name": "walk_page_mapping",
      "external": true,
      "loc": "mm/pagewalk.c:660",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range",
        "mm/mapping_dirty_helpers.c:wp_shared_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258208,
      "name": "walk_page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int walk_page_mapping(struct address_space * mapping, long unsigned int first_index, long unsigned int nr, const struct mm_walk_ops * ops, void * private)
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
