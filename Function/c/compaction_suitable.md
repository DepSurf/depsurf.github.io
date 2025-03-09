# Function: <code>compaction_suitable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int compaction_suitable(struct zone * zone, int order, int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644288,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1326",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644288,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749488,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1421",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749488,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815056,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1408",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815056,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855232,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1442",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855232,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946224,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1466",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946224,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082448,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1466",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082448,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160352,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:1467",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160352,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230096,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230096,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288688,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288688,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481088,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2012",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481088,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522208,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2167",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_zones",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522208,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544272,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2206",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544272,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807472,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2198",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807472,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196064,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2220",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196064,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682672,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2219",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682672,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
bool compaction_suitable(struct zone * zone, int order, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582892016,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2279",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892016,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool compaction_suitable(struct zone * zone, int order, int highest_zoneidx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583063840,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2330",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063840,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492694928,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492694928,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226533336,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226533336,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286027536,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286027536,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272697318,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272697318,
      "name": "compaction_suitable",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257536,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257536,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581204192,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204192,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248736,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248736,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
enum compact_result compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx)
```

```json
{
  "name": "compaction_suitable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312352,
      "name": "compaction_suitable",
      "external": true,
      "loc": "mm/compaction.c:2001",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:wakeup_kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/compaction.c:compact_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312352,
      "name": "compaction_suitable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>enum compact_result</code>
</li>
</ul>
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
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int alloc_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, alloc_flags, highest_zoneidx</code> ➡️ <code>zone, order, highest_zoneidx</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum compact_result</code> ➡️ <code>bool</code>
</li>
</ul>
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
