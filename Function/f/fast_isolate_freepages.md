# Function: <code>fast_isolate_freepages</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223696,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1274",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223696,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282256,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282256,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473952,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1280",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473952,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1820
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515216,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1345",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515216,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1870
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
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581535376,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1381",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535376,
      "name": "fast_isolate_freepages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1867
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1373",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804016,
      "name": "fast_isolate_freepages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1830
    },
    {
      "addr": 18446744071592196621,
      "name": "fast_isolate_freepages.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1406",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185040,
      "name": "fast_isolate_freepages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2079
    },
    {
      "addr": 18446744071593972642,
      "name": "fast_isolate_freepages.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1396",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671456,
      "name": "fast_isolate_freepages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1996
    },
    {
      "addr": 18446744071596029688,
      "name": "fast_isolate_freepages.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1448",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882336,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2092
    },
    {
      "addr": 18446744071596551662,
      "name": "fast_isolate_freepages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1486",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_freepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583053648,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2275
    },
    {
      "addr": 18446744071597455355,
      "name": "fast_isolate_freepages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492688664,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492688664,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226524996,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226524996,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286018528,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286018528,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2032
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272690328,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272690328,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1198
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251104,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251104,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197760,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197760,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242304,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242304,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```

```json
{
  "name": "fast_isolate_freepages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305920,
      "name": "fast_isolate_freepages",
      "external": false,
      "loc": "mm/compaction.c:1275",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305920,
      "name": "fast_isolate_freepages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
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
long unsigned int fast_isolate_freepages(struct compact_control * cc)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control * cc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void fast_isolate_freepages(struct compact_control * cc)
```
</details>
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
