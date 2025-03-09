# Function: <code>pasid_to_svm_sdev</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926928,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:250",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926928,
      "name": "pasid_to_svm_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586809200,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:213",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586809200,
      "name": "pasid_to_svm_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371376,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:285",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371376,
      "name": "pasid_to_svm_sdev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588682560,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:280",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_page_response"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588682560,
      "name": "pasid_to_svm_sdev",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590160739,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:266",
      "file": "drivers/iommu/intel/svm.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590473415,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:264",
      "file": "drivers/iommu/intel/svm.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pasid_to_svm_sdev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590825957,
      "name": "pasid_to_svm_sdev",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:286",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```
</details>
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
int pasid_to_svm_sdev(struct device * dev, unsigned int pasid, struct intel_svm * * rsvm, struct intel_svm_dev * * rsdev)
```
</details>
</li>
</ul>
