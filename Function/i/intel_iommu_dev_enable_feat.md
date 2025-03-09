# Function: <code>intel_iommu_dev_enable_feat</code>

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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970992,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5624",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970992,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586116624,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5925",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116624,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586867248,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5953",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586867248,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586918928,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5359",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918928,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586800160,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5405",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800160,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587356960,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5464",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587356960,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668816,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4829",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668816,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590119504,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4704",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590119504,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590432768,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4662",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590432768,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590779408,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4561",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590779408,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585876992,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5925",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876992,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585736768,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5925",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736768,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586066640,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5925",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066640,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```

```json
{
  "name": "intel_iommu_dev_enable_feat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586174816,
      "name": "intel_iommu_dev_enable_feat",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5925",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586174816,
      "name": "intel_iommu_dev_enable_feat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_iommu_dev_enable_feat(struct device * dev, enum iommu_dev_features feat)
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
