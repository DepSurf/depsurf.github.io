# Function: <code>amd_iommu_release_device</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586807136,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2168",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586807136,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586866512,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2260",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586866512,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749120,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1720",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749120,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1764",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302656,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071592469342,
      "name": "amd_iommu_release_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588615952,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1786",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615952,
      "name": "amd_iommu_release_device",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590078496,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1905",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590078496,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590390144,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1930",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590390144,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
void amd_iommu_release_device(struct device * dev)
```

```json
{
  "name": "amd_iommu_release_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590735648,
      "name": "amd_iommu_release_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1978",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590735648,
      "name": "amd_iommu_release_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void amd_iommu_release_device(struct device * dev)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
