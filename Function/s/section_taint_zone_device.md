# Function: <code>section_taint_zone_device</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void section_taint_zone_device(long unsigned int pfn)
```

```json
{
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591273565,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:733",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591273565,
      "name": "section_taint_zone_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void section_taint_zone_device(long unsigned int pfn)
```

```json
{
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592207806,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:676",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207806,
      "name": "section_taint_zone_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void section_taint_zone_device(long unsigned int pfn)
```

```json
{
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593985451,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:675",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985451,
      "name": "section_taint_zone_device",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596420971,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:666",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
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
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596961046,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:660",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
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
  "name": "section_taint_zone_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597888678,
      "name": "section_taint_zone_device",
      "external": false,
      "loc": "mm/memory_hotplug.c:729",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
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
void section_taint_zone_device(long unsigned int pfn)
```
</details>
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
void section_taint_zone_device(long unsigned int pfn)
```
</details>
</li>
</ul>
