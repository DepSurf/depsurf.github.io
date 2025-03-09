# Function: <code>get_scan_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580566195,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:1961",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_lruvec"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580659129,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2088",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580726345,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2100",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762201,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2160",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580849577,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2184",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580986205,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2114",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581063261,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2282",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcg"
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115904,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2250",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115904,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172800,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172800,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352272,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2239",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352272,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395760,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2246",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395760,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416544,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2436",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416544,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2574",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669248,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1430
    },
    {
      "addr": 18446744071592191600,
      "name": "get_scan_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2680",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041728,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    },
    {
      "addr": 18446744071593967527,
      "name": "get_scan_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2941",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521968,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
    },
    {
      "addr": 18446744071596026625,
      "name": "get_scan_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:3025",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724928,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
    },
    {
      "addr": 18446744071596548730,
      "name": "get_scan_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void get_scan_count(struct lruvec * lruvec, struct scan_control * sc, long unsigned int * nr)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2325",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_lruvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894384,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1506
    },
    {
      "addr": 18446744071597452361,
      "name": "get_scan_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492552672,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492552672,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226415412,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226415412,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285855712,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285855712,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272598700,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272598700,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141648,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141648,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088592,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088592,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132848,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132848,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```

```json
{
  "name": "get_scan_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195328,
      "name": "get_scan_count",
      "external": false,
      "loc": "mm/vmscan.c:2304",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195328,
      "name": "get_scan_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1153
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
void get_scan_count(struct lruvec * lruvec, struct mem_cgroup * memcg, struct scan_control * sc, long unsigned int * nr, long unsigned int * lru_pages)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * lru_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, memcg, sc, nr, lru_pages</code> ➡️ <code>lruvec, sc, nr</code>
</li>
</ul>
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
