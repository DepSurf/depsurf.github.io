# Function: <code>shrink_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660960,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2509",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660960,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728240,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2521",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728240,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763984,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2561",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763984,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851360,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2585",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851360,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988000,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2521",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988000,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065072,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2691",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065072,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128160,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2659",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128160,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186048,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186048,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370992,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2677",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370992,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1324
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414704,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2676",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:shrink_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414704,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1342
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435984,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2874",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435984,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:3029",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689264,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
    },
    {
      "addr": 18446744071592191994,
      "name": "shrink_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:3135",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063184,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
    },
    {
      "addr": 18446744071593967832,
      "name": "shrink_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:6159",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535840,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071596026807,
      "name": "shrink_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:6517",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744992,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1309
    },
    {
      "addr": 18446744071596548971,
      "name": "shrink_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:5881",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913328,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
    },
    {
      "addr": 18446744071597452565,
      "name": "shrink_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492566736,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492566736,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226429012,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226429012,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285874592,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285874592,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1528
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272610062,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272610062,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154896,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154896,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101760,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101760,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146096,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146096,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
```

```json
{
  "name": "shrink_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208656,
      "name": "shrink_node",
      "external": false,
      "loc": "mm/vmscan.c:2756",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:do_try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208656,
      "name": "shrink_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
bool shrink_node(pg_data_t * pgdat, struct scan_control * sc)
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
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
