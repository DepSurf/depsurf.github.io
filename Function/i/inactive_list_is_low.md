# Function: <code>inactive_list_is_low</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580566770,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:1925",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649280,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2010",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649280,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716560,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2044",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716560,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct mem_cgroup * memcg, struct scan_control * sc, bool actual_reclaim)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751744,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2079",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751744,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct mem_cgroup * memcg, struct scan_control * sc, bool actual_reclaim)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838944,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2103",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838944,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct mem_cgroup * memcg, struct scan_control * sc, bool actual_reclaim)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975056,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2033",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975056,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct mem_cgroup * memcg, struct scan_control * sc, bool actual_reclaim)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051728,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2201",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051728,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115376,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2176",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115376,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172272,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172272,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492552112,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492552112,
      "name": "inactive_list_is_low.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226414776,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226414776,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285854992,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285854992,
      "name": "inactive_list_is_low.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272598208,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272598208,
      "name": "inactive_list_is_low.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141120,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141120,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088064,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088064,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132320,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132320,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```

```json
{
  "name": "inactive_list_is_low",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194768,
      "name": "inactive_list_is_low",
      "external": false,
      "loc": "mm/vmscan.c:2230",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194768,
      "name": "inactive_list_is_low",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param added. </b>
<code>bool actual_reclaim</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, file, sc</code> ➡️ <code>lruvec, file, memcg, sc, actual_reclaim</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool trace</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>bool actual_reclaim</code>
</li>
<li>
<b>Param reordered. </b>
<code>lruvec, file, memcg, sc, actual_reclaim</code> ➡️ <code>lruvec, file, sc, trace</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool inactive_list_is_low(struct lruvec * lruvec, bool file, struct scan_control * sc, bool trace)
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
