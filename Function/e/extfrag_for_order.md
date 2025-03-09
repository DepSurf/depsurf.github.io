# Function: <code>extfrag_for_order</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469712,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1104",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469712,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490448,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1116",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490448,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1122",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592192857,
      "name": "extfrag_for_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071581749104,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1128",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593968756,
      "name": "extfrag_for_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582131376,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1115",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596027572,
      "name": "extfrag_for_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582607024,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1116",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596549969,
      "name": "extfrag_for_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582815712,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```

```json
{
  "name": "extfrag_for_order",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "extfrag_for_order",
      "external": true,
      "loc": "mm/vmstat.c:1119",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:__compact_finished"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597453634,
      "name": "extfrag_for_order.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071582990192,
      "name": "extfrag_for_order",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int extfrag_for_order(struct zone * zone, unsigned int order)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
