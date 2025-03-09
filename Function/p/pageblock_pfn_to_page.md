# Function: <code>pageblock_pfn_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone * zone)
```

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634032,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/compaction.c:91",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_freepages_range",
        "mm/compaction.c:isolate_migratepages_range",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634032,
      "name": "pageblock_pfn_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580750518,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:142",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580816094,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:144",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855963,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:154",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946962,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:154",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083523,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:154",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161427,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:154",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581230963,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289596,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581479488,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:184",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581521056,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:182",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541446,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:181",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581801932,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:186",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582194548,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582681252,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:347",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582890271,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:361",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583062143,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:378",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_range",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492695960,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226534524,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
        "mm/compaction.c:isolate_migratepages_range",
        "mm/compaction.c:isolate_freepages_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286028708,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272697868,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258444,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581205100,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249644,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_pfn_to_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313283,
      "name": "pageblock_pfn_to_page",
      "external": false,
      "loc": "mm/internal.h:150",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compaction_alloc",
        "mm/compaction.c:isolate_migratepages_range",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct page * pageblock_pfn_to_page(long unsigned int start_pfn, long unsigned int end_pfn, struct zone * zone)
```
</details>
</li>
</ul>
