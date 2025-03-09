# Function: <code>adjust_present_page_count</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void adjust_present_page_count(struct zone * zone, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591612558,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:866",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757648,
      "name": "adjust_present_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void adjust_present_page_count(struct page * page, struct memory_group * group, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039376,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:1010",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039376,
      "name": "adjust_present_page_count",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void adjust_present_page_count(struct page * page, struct memory_group * group, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582469312,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:1009",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469312,
      "name": "adjust_present_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void adjust_present_page_count(struct page * page, struct memory_group * group, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983696,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:1005",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983696,
      "name": "adjust_present_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void adjust_present_page_count(struct page * page, struct memory_group * group, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195216,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:999",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195216,
      "name": "adjust_present_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void adjust_present_page_count(struct page * page, struct memory_group * group, long int nr_pages)
```

```json
{
  "name": "adjust_present_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380112,
      "name": "adjust_present_page_count",
      "external": true,
      "loc": "mm/memory_hotplug.c:1068",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380112,
      "name": "adjust_present_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void adjust_present_page_count(struct zone * zone, long int nr_pages)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>struct memory_group * group</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone * zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, nr_pages</code> ➡️ <code>page, group, nr_pages</code>
</li>
</ul>
</details>
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
