# Function: <code>setup_iommu_pool_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583117850,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "lib/iommu-common.c:33",
      "file": "lib/iommu-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_pool_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583412029,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "lib/iommu-common.c:33",
      "file": "lib/iommu-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_pool_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583537709,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "lib/iommu-common.c:33",
      "file": "lib/iommu-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_pool_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583575421,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "lib/iommu-common.c:33",
      "file": "lib/iommu-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_pool_init"
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
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583821245,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "lib/iommu-common.c:34",
      "file": "lib/iommu-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_pool_init"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int setup_iommu_pool_hash()
```

```json
{
  "name": "setup_iommu_pool_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302415716,
      "name": "setup_iommu_pool_hash",
      "external": false,
      "loc": "arch/powerpc/kernel/iommu.c:65",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302415716,
      "name": "setup_iommu_pool_hash",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 176
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int setup_iommu_pool_hash()
```
</details>
</li>
</ul>
