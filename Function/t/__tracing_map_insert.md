# Function: <code>__tracing_map_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580287991,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:411",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580331607,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:411",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580343783,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:414",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580397220,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:414",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580458992,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:522",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514560,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert",
        "kernel/trace/tracing_map.c:tracing_map_insert"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580569568,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569568,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616720,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616720,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716608,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716608,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706048,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706048,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710224,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710224,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:516",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888160,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071592171983,
      "name": "__tracing_map_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:516",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123088,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071593945564,
      "name": "__tracing_map_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:516",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433152,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071596006042,
      "name": "__tracing_map_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:516",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529984,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071596524471,
      "name": "__tracing_map_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:516",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641952,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071597425125,
      "name": "__tracing_map_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491919640,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup"
      ],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491917224,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285014268,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_lookup"
      ],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285010896,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580585520,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585520,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580532144,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532144,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580576768,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576768,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```

```json
{
  "name": "__tracing_map_insert",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580633504,
      "name": "__tracing_map_insert",
      "external": false,
      "loc": "kernel/trace/tracing_map.c:513",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/tracing_map.c:tracing_map_lookup",
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633504,
      "name": "__tracing_map_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct tracing_map_elt * __tracing_map_insert(struct tracing_map * map, void * key, bool lookup_only)
```
</details>
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
