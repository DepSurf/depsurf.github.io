# Function: <code>intel_pasid_alloc_id</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742448,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742448,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977416,
      "name": "intel_pasid_alloc_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585974128,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119616,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119616,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585879984,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879984,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585739760,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585739760,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069632,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069632,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "intel_pasid_alloc_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177840,
      "name": "intel_pasid_alloc_id",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:31",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177840,
      "name": "intel_pasid_alloc_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```
</details>
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
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
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pasid_alloc_id(void * ptr, int start, int end, gfp_t gfp)
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
