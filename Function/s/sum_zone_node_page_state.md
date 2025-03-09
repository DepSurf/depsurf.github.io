# Function: <code>sum_zone_node_page_state</code>

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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709024,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:791",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709024,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774848,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:791",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774848,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811296,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:791",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_numastat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811296,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901136,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:958",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901136,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036944,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:958",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036944,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114528,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:958",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:si_meminfo_node",
        "mm/vmscan.c:shrink_node_memcg",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114528,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179200,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179200,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237312,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237312,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581426096,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426096,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469360,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:973",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469360,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490096,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:985",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490096,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748816,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:994",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748816,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131072,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:995",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131072,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606592,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:982",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606592,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815216,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:983",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_count",
        "mm/show_mem.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815216,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989696,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:986",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:prepare_scan_control",
        "mm/show_mem.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989696,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492632584,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492632584,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285949920,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285949920,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206160,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206160,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152912,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152912,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197360,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197360,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
```

```json
{
  "name": "sum_zone_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260640,
      "name": "sum_zone_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:959",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/page_alloc.c:si_meminfo_node",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260640,
      "name": "sum_zone_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
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
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item)
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
