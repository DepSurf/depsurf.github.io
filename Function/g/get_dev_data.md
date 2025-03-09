# Function: <code>get_dev_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_data",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:184",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "get_dev_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_data",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:351",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_data",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:352",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_data",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585317116,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:321",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585310400,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585560079,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:317",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551216,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684671,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:327",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675632,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585911839,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902912,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586055167,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:302",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045760,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816143,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:302",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585806736,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585675327,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:302",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665920,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586005183,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:302",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995776,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```

```json
{
  "name": "get_dev_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586113471,
      "name": "get_dev_data",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:302",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586103744,
      "name": "get_dev_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_dev_data * get_dev_data(struct device * dev)
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
