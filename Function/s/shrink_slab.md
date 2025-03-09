# Function: <code>shrink_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550496,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:406",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:shrink_zone"
      ],
      "caller_func": [
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:shrink_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550496,
      "name": "shrink_slab.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, long unsigned int nr_scanned, long unsigned int nr_eligible)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661494,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:419",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641584,
      "name": "shrink_slab.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071580642560,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, long unsigned int nr_scanned, long unsigned int nr_eligible)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580728774,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:454",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708576,
      "name": "shrink_slab.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
    },
    {
      "addr": 18446744071580709632,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, long unsigned int nr_scanned, long unsigned int nr_eligible)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764706,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:455",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743296,
      "name": "shrink_slab.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
    },
    {
      "addr": 18446744071580744272,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, long unsigned int nr_scanned, long unsigned int nr_eligible)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852082,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:460",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830368,
      "name": "shrink_slab.part.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
    },
    {
      "addr": 18446744071580831360,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988957,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:499",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967488,
      "name": "shrink_slab.part.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
    },
    {
      "addr": 18446744071580994953,
      "name": "shrink_slab.part.45.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580969408,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044496,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:680",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044496,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581109984,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:692",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109984,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581166720,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166720,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363008,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:652",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363008,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406608,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:645",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406608,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427616,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:845",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427616,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679552,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:891",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679552,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056304,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:903",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056304,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528896,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:980",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:drop_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528896,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582731696,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:1033",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:drop_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731696,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928192,
      "name": "shrink_slab",
      "external": true,
      "loc": "mm/shrinker.c:612",
      "file": "mm/shrinker.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:drop_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928192,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492548760,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492548760,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226409508,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226409508,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285844896,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285844896,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272592158,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272592158,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581135568,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135568,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581082512,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082512,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581126768,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126768,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, int priority)
```

```json
{
  "name": "shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581189296,
      "name": "shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:695",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:drop_slab_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189296,
      "name": "shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup * memcg, long unsigned int nr_scanned, long unsigned int nr_eligible)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int priority</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_scanned</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_eligible</code>
</li>
</ul>
</details>
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
