# Function: <code>walk_zones_in_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file * m, pg_data_t * pgdat, void (*)(struct seq_file *, pg_data_t *, struct zone *) print)
```

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599648,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:903",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:frag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:unusable_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599648,
      "name": "walk_zones_in_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file * m, pg_data_t * pgdat, void (*)(struct seq_file *, pg_data_t *, struct zone *) print)
```

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701680,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1123",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:unusable_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701680,
      "name": "walk_zones_in_node",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void walk_zones_in_node(struct seq_file * m, pg_data_t * pgdat, void (*)(struct seq_file *, pg_data_t *, struct zone *) print)
```

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767488,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1123",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:unusable_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767488,
      "name": "walk_zones_in_node",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580808048,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1132",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808048,
      "name": "walk_zones_in_node.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580897248,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1326",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897248,
      "name": "walk_zones_in_node.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581033136,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1327",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033136,
      "name": "walk_zones_in_node.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110704,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1331",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110704,
      "name": "walk_zones_in_node.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581175408,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1327",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175408,
      "name": "walk_zones_in_node.constprop.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581233536,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233536,
      "name": "walk_zones_in_node.constprop.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581421813,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1341",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581464800,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1388",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581485312,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1411",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581740560,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1419",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582122192,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1442",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582596560,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1437",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582804176,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1447",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582979056,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1451",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492623608,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492623608,
      "name": "walk_zones_in_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226473340,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226473340,
      "name": "walk_zones_in_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285944144,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285944144,
      "name": "walk_zones_in_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272648690,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272648690,
      "name": "walk_zones_in_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581202384,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202384,
      "name": "walk_zones_in_node.constprop.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149136,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149136,
      "name": "walk_zones_in_node.constprop.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581193584,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193584,
      "name": "walk_zones_in_node.constprop.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_zones_in_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581256864,
      "name": "walk_zones_in_node",
      "external": false,
      "loc": "mm/vmstat.c:1329",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show",
        "mm/vmstat.c:zoneinfo_show",
        "mm/vmstat.c:frag_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256864,
      "name": "walk_zones_in_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void walk_zones_in_node(struct seq_file * m, pg_data_t * pgdat, void (*)(struct seq_file *, pg_data_t *, struct zone *) print)
```
</details>
</li>
</ul>
