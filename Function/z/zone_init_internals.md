# Function: <code>zone_init_internals</code>

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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604769870,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6481",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604888901,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6673",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604922836,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609235712,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6720",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612302247,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6950",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614443808,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:7168",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592799716,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:7412",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592799716,
      "name": "zone_init_internals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594699959,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:7537",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594699959,
      "name": "zone_init_internals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627858933,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:7722",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619613220,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/mm_init.c:1364",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init_core",
        "mm/mm_init.c:free_area_init_core_hotplug"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621917476,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/mm_init.c:1373",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init_core",
        "mm/mm_init.c:free_area_init_core_hotplug"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510961392,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243449304,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297811420,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297811420,
      "name": "zone_init_internals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270688676,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604828296,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604797357,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604905480,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
  "name": "zone_init_internals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604927017,
      "name": "zone_init_internals",
      "external": false,
      "loc": "mm/page_alloc.c:6693",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void zone_init_internals(struct zone * zone, enum zone_type idx, int nid, long unsigned int remaining_pages)
```
</details>
</li>
</ul>
