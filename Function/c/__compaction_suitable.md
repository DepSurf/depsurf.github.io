# Function: <code>__compaction_suitable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580644316,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1281",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_suitable"
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
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753928,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1373",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742208,
      "name": "__compaction_suitable.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819260,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1365",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808240,
      "name": "__compaction_suitable.part.39",
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
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580859735,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1399",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848368,
      "name": "__compaction_suitable.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580950728,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1423",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939344,
      "name": "__compaction_suitable.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075168,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1423",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075168,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581153056,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1424",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153056,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219536,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219536,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278096,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278096,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469088,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1969",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469088,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510256,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2117",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510256,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532368,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2156",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532368,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2148",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793120,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071592195567,
      "name": "__compaction_suitable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2170",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180800,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071593972143,
      "name": "__compaction_suitable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2169",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666112,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071596029191,
      "name": "__compaction_suitable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
bool __compaction_suitable(struct zone * zone, int order, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2250",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876464,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071596551174,
      "name": "__compaction_suitable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
bool __compaction_suitable(struct zone * zone, int order, int highest_zoneidx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:2301",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047696,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071597454638,
      "name": "__compaction_suitable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492681840,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492681840,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226523580,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226523580,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286013264,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286013264,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272689074,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272689074,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246944,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246944,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193616,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193616,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238144,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238144,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```

```json
{
  "name": "__compaction_suitable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301680,
      "name": "__compaction_suitable",
      "external": false,
      "loc": "mm/compaction.c:1958",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compaction_zonelist_suitable",
        "mm/compaction.c:compaction_suitable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301680,
      "name": "__compaction_suitable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
enum compact_result __compaction_suitable(struct zone * zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target)
```
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
<code>zone, order, alloc_flags, highest_zoneidx, wmark_target</code> ➡️ <code>zone, order, highest_zoneidx, wmark_target</code>
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
