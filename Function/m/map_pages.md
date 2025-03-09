# Function: <code>map_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580638356,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:58",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range"
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
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741568,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:66",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741568,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807408,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:66",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807408,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847488,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:67",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847488,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938464,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:68",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938464,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074672,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:68",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074672,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void map_pages(struct list_head * list)
```

```json
{
  "name": "map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152560,
      "name": "map_pages",
      "external": false,
      "loc": "mm/compaction.c:69",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_freepages_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152560,
      "name": "map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
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
void map_pages(struct list_head * list)
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void map_pages(struct list_head * list)
```
</details>
</li>
</ul>
