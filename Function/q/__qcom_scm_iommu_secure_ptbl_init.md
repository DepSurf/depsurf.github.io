# Function: <code>__qcom_scm_iommu_secure_ptbl_init</code>

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
int __qcom_scm_iommu_secure_ptbl_init(struct device * dev, u64 addr, u32 size, u32 spare)
```

```json
{
  "name": "__qcom_scm_iommu_secure_ptbl_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501494832,
      "name": "__qcom_scm_iommu_secure_ptbl_init",
      "external": true,
      "loc": "drivers/firmware/qcom_scm-64.c:439",
      "file": "drivers/firmware/qcom_scm-64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/qcom_scm.c:qcom_scm_iommu_secure_ptbl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501494832,
      "name": "__qcom_scm_iommu_secure_ptbl_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __qcom_scm_iommu_secure_ptbl_init(struct device * dev, u64 addr, u32 size, u32 spare)
```

```json
{
  "name": "__qcom_scm_iommu_secure_ptbl_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234032904,
      "name": "__qcom_scm_iommu_secure_ptbl_init",
      "external": true,
      "loc": "drivers/firmware/qcom_scm-32.c:594",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/qcom_scm.c:qcom_scm_iommu_secure_ptbl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234032904,
      "name": "__qcom_scm_iommu_secure_ptbl_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int __qcom_scm_iommu_secure_ptbl_init(struct device * dev, u64 addr, u32 size, u32 spare)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __qcom_scm_iommu_secure_ptbl_init(struct device * dev, u64 addr, u32 size, u32 spare)
```
</details>
</li>
</ul>
