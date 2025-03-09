# Function: <code>zone_pcp_enable</code>

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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581728288,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:8802",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728288,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750688,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:9031",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750688,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030768,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:9294",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030768,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458992,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:9346",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458992,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972944,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:9509",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972944,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184784,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:6416",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184784,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void zone_pcp_enable(struct zone * zone)
```

```json
{
  "name": "zone_pcp_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368896,
      "name": "zone_pcp_enable",
      "external": true,
      "loc": "mm/page_alloc.c:6558",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory-failure.c:get_hwpoison_page",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368896,
      "name": "zone_pcp_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void zone_pcp_enable(struct zone * zone)
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
