# Function: <code>fast_find_migrateblock</code>

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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581230837,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1623",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289467,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581467856,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1635",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467856,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508976,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1703",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508976,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531072,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1739",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531072,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1731",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793936,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    },
    {
      "addr": 18446744071592195684,
      "name": "fast_find_migrateblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1764",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181680,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071593972260,
      "name": "fast_find_migrateblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1751",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667104,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071596029308,
      "name": "fast_find_migrateblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1817",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876976,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071596551248,
      "name": "fast_find_migrateblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
```

```json
{
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1866",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048368,
      "name": "fast_find_migrateblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071597454739,
      "name": "fast_find_migrateblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492695868,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226534400,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286028600,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272697858,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581258315,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581204971,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581249515,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
  "name": "fast_find_migrateblock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313150,
      "name": "fast_find_migrateblock",
      "external": false,
      "loc": "mm/compaction.c:1624",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_zone"
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
long unsigned int fast_find_migrateblock(struct compact_control * cc)
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
