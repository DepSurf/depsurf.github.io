# Function: <code>blk_cgroup_congested</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581019314,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:291",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581346406,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:291",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083277,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:298",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581456745,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:298",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581139261,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581520905,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581324157,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:278",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581728405,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:278",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:cgroup_throttle_swaprate"
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
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581366616,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:268",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:page_cache_sync_ra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776453,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:268",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:cgroup_throttle_swaprate"
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
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581386082,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:268",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:page_cache_sync_ra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804009,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:268",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:cgroup_throttle_swaprate"
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
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581635202,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:273",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:page_cache_sync_ra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088937,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:273",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__cgroup_throttle_swaprate"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool blk_cgroup_congested()
```

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585812064,
      "name": "blk_cgroup_congested",
      "external": true,
      "loc": "block/blk-cgroup.c:2017",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:__cgroup_throttle_swaprate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812064,
      "name": "blk_cgroup_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool blk_cgroup_congested()
```

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593936,
      "name": "blk_cgroup_congested",
      "external": true,
      "loc": "block/blk-cgroup.c:2040",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:__cgroup_throttle_swaprate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593936,
      "name": "blk_cgroup_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool blk_cgroup_congested()
```

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586852096,
      "name": "blk_cgroup_congested",
      "external": true,
      "loc": "block/blk-cgroup.c:2132",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:__folio_throttle_swaprate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852096,
      "name": "blk_cgroup_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool blk_cgroup_congested()
```

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129408,
      "name": "blk_cgroup_congested",
      "external": true,
      "loc": "block/blk-cgroup.c:2148",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_sync_ra",
        "mm/readahead.c:page_cache_sync_ra",
        "mm/swapfile.c:__folio_throttle_swaprate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129408,
      "name": "blk_cgroup_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492513720,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492944528,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226383444,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226730524,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285803184,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286358096,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272570874,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272861732,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581108109,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581489641,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581055181,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431897,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581099309,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581480953,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_cgroup_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161556,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581545702,
      "name": "blk_cgroup_congested",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:300",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:mem_cgroup_throttle_swaprate"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool blk_cgroup_congested()
```
</details>
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
