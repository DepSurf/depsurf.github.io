# Function: <code>node_page_state_pages</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581462024,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1006",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469616,
      "name": "node_page_state_pages",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581482955,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1018",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490352,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581738697,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1024",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749008,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582119824,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1025",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131280,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582593786,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1012",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606832,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582800968,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1013",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815520,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
```

```json
{
  "name": "node_page_state_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582975560,
      "name": "node_page_state_pages",
      "external": true,
      "loc": "mm/vmstat.c:1016",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:zoneinfo_show_print",
        "mm/vmstat.c:node_page_state"
      ],
      "caller_func": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:__node_reclaim",
        "drivers/base/node.c:node_read_vmstat",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo",
        "drivers/base/node.c:node_read_meminfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990000,
      "name": "node_page_state_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
long unsigned int node_page_state_pages(struct pglist_data * pgdat, enum node_stat_item item)
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
