# Function: <code>move_pages_to_lru</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123920,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1879",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123920,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181808,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181808,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581356336,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1847",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356336,
      "name": "move_pages_to_lru.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400368,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1826",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400368,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1005
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420960,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:2021",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420960,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671504,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:2154",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671504,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1247
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043872,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:2262",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043872,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492562056,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492562056,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226424716,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226424716,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285868448,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285868448,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1744
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272606100,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272606100,
      "name": "move_pages_to_lru",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150656,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150656,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097568,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097568,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141856,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141856,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```

```json
{
  "name": "move_pages_to_lru",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581204400,
      "name": "move_pages_to_lru",
      "external": false,
      "loc": "mm/vmscan.c:1878",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204400,
      "name": "move_pages_to_lru",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int move_pages_to_lru(struct lruvec * lruvec, struct list_head * list)
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
