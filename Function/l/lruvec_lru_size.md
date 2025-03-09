# Function: <code>lruvec_lru_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580649232,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:237",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649232,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716336,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:243",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716336,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751472,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:244",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751472,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838672,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:245",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838672,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974800,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:274",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974800,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051472,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:343",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051472,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115056,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:355",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115056,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172016,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172016,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581352410,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:320",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364576,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395906,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:313",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408176,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581416703,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:545",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581669401,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:591",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582041886,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:588",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582522126,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:602",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582725077,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:654",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
  "name": "lruvec_lru_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582894533,
      "name": "lruvec_lru_size",
      "external": false,
      "loc": "mm/vmscan.c:360",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:get_scan_count"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492551864,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492551864,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226414588,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226414588,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285854672,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285854672,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272597964,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272597964,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140864,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140864,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087808,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087808,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132064,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132064,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```

```json
{
  "name": "lruvec_lru_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194512,
      "name": "lruvec_lru_size",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/workingset.c:workingset_refault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194512,
      "name": "lruvec_lru_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zone_idx</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int lruvec_lru_size(struct lruvec * lruvec, enum lru_list lru, int zone_idx)
```
</details>
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
