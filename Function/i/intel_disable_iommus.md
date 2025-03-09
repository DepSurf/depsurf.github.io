# Function: <code>intel_disable_iommus</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596638746,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4728",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602968777,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4633",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603140074,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4675",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604944611,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4684",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605052295,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4479",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605089221,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_disable_iommus()
```

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586866832,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4634",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839328,
      "name": "intel_disable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_disable_iommus()
```

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918512,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4031",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895552,
      "name": "intel_disable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void intel_disable_iommus()
```

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586799744,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4117",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586775120,
      "name": "intel_disable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void intel_disable_iommus()
```

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587356490,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4112",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330240,
      "name": "intel_disable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void intel_disable_iommus()
```

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588668402,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3857",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644960,
      "name": "intel_disable_iommus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628086771,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3733",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619852451,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3620",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622161331,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3469",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604988834,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604953145,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605069544,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "intel_disable_iommus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605093415,
      "name": "intel_disable_iommus",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void intel_disable_iommus()
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void intel_disable_iommus()
```
</details>
</li>
</ul>
