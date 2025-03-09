# Function: <code>pageblock_skip_persistent</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580938383,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:226",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
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
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581074511,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:226",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
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
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581152207,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220176,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220176,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278736,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278736,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469520,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469520,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510688,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:244",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510688,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532832,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:243",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532832,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795056,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:243",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795056,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582194609,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:243",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674336,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:238",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674336,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885312,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:264",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885312,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057072,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:289",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057072,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492681160,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492681160,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226522108,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226522108,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286012320,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286012320,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272688576,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272688576,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247584,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247584,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194240,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194240,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238784,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238784,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```

```json
{
  "name": "pageblock_skip_persistent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302320,
      "name": "pageblock_skip_persistent",
      "external": false,
      "loc": "mm/compaction.c:227",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:__reset_isolation_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302320,
      "name": "pageblock_skip_persistent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
bool pageblock_skip_persistent(struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool pageblock_skip_persistent(struct page * page)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
