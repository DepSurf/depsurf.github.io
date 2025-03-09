# Function: <code>remove_pfn_range_from_zone</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153216,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153216,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591171568,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:472",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591171568,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591667184,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:472",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:pageunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591667184,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591611344,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:514",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591611344,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592784704,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:461",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592784704,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594683392,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:472",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594683392,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596419776,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:460",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596419776,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596959840,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:459",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596959840,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597887472,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:527",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_deinit_memmap_on_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597887472,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503904192,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503904192,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286552080,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286552080,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1216
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589755504,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589755504,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589479728,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589479728,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198912,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198912,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "remove_pfn_range_from_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590249312,
      "name": "remove_pfn_range_from_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:470",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590249312,
      "name": "remove_pfn_range_from_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void remove_pfn_range_from_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
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
