# Function: <code>update_cached_migrate</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581231170,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:406",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289796,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581479823,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581521381,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:424",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541755,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:423",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:421",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793360,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071592195592,
      "name": "update_cached_migrate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:420",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181040,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071593972168,
      "name": "update_cached_migrate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:415",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666368,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071596029216,
      "name": "update_cached_migrate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:437",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876656,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071596551206,
      "name": "update_cached_migrate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:461",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047888,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071597454670,
      "name": "update_cached_migrate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492696076,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226534712,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286005504,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286005504,
      "name": "update_cached_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272698270,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258644,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581205300,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249844,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
  "name": "update_cached_migrate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313479,
      "name": "update_cached_migrate",
      "external": false,
      "loc": "mm/compaction.c:407",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void update_cached_migrate(struct compact_control * cc, long unsigned int pfn)
```
</details>
</li>
</ul>
