# Function: <code>of_iommu_configure</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```

```json
{
  "name": "of_iommu_configure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498867104,
      "name": "of_iommu_configure",
      "external": true,
      "loc": "drivers/iommu/of_iommu.c:151",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/device.c:of_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498867104,
      "name": "of_iommu_configure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```

```json
{
  "name": "of_iommu_configure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231454600,
      "name": "of_iommu_configure",
      "external": true,
      "loc": "drivers/iommu/of_iommu.c:151",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/device.c:of_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231454600,
      "name": "of_iommu_configure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```

```json
{
  "name": "of_iommu_configure",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292061664,
      "name": "of_iommu_configure",
      "external": true,
      "loc": "drivers/iommu/of_iommu.c:151",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/device.c:of_dma_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292061664,
      "name": "of_iommu_configure",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
  "name": "of_iommu_configure",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_iommu_configure",
      "external": false,
      "loc": "include/linux/of_iommu.h:27",
      "file": "drivers/of/device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const struct iommu_ops * of_iommu_configure(struct device * dev, struct device_node * master_np)
```
</details>
</li>
</ul>
