# Function: <code>shrink_page_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head * page_list, struct zone * zone, struct scan_control * sc, enum ttu_flags ttu_flags, long unsigned int * ret_nr_dirty, long unsigned int * ret_nr_unqueued_dirty, long unsigned int * ret_nr_congested, long unsigned int * ret_nr_writeback, long unsigned int * ret_nr_immediate, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560688,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:880",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_clean_pages_from_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560688,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, long unsigned int * ret_nr_dirty, long unsigned int * ret_nr_unqueued_dirty, long unsigned int * ret_nr_congested, long unsigned int * ret_nr_writeback, long unsigned int * ret_nr_immediate, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652704,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:900",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652704,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2459
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, long unsigned int * ret_nr_dirty, long unsigned int * ret_nr_unqueued_dirty, long unsigned int * ret_nr_congested, long unsigned int * ret_nr_writeback, long unsigned int * ret_nr_immediate, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719824,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:935",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719824,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2558
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755184,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:948",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755184,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2914
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842480,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:960",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842480,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3004
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978768,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:927",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978768,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3101
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055792,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1100",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055792,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3101
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool force_reclaim)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120480,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120480,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2992
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177520,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177520,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581359712,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1076",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359712,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2832
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
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581403136,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1070",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403136,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2995
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
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422144,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1270",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422144,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3269
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
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1364",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674768,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3824
    },
    {
      "addr": 18446744071592191669,
      "name": "shrink_page_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1528",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_page_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048256,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3161
    },
    {
      "addr": 18446744071593967588,
      "name": "shrink_page_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492557768,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492557768,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3012
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226420216,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226420216,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3644
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285862576,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285862576,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4188
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272602732,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272602732,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2646
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146368,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146368,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093312,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093312,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2948
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137568,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137568,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
long unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, enum ttu_flags ttu_flags, struct reclaim_stat * stat, bool ignore_references)
```

```json
{
  "name": "shrink_page_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200112,
      "name": "shrink_page_list",
      "external": false,
      "loc": "mm/vmscan.c:1119",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200112,
      "name": "shrink_page_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2983
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pglist_data * pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone * zone</code>
</li>
</ul>
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
<code>struct reclaim_stat * stat</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * ret_nr_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * ret_nr_unqueued_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * ret_nr_congested</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * ret_nr_writeback</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * ret_nr_immediate</code>
</li>
<li>
<b>Param reordered. </b>
<code>page_list, pgdat, sc, ttu_flags, ret_nr_dirty, ret_nr_unqueued_dirty, ret_nr_congested, ret_nr_writeback, ret_nr_immediate, force_reclaim</code> ➡️ <code>page_list, pgdat, sc, ttu_flags, stat, force_reclaim</code>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ignore_references</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_reclaim</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum ttu_flags ttu_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>page_list, pgdat, sc, ttu_flags, stat, ignore_references</code> ➡️ <code>page_list, pgdat, sc, stat, ignore_references</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int shrink_page_list(struct list_head * page_list, struct pglist_data * pgdat, struct scan_control * sc, struct reclaim_stat * stat, bool ignore_references)
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
