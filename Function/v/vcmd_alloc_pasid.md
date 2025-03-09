# Function: <code>vcmd_alloc_pasid</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu * iommu, unsigned int * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:30",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874803,
      "name": "vcmd_alloc_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586870800,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:30",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480460,
      "name": "vcmd_alloc_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586919600,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:29",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420887,
      "name": "vcmd_alloc_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071586801136,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:29",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477264,
      "name": "vcmd_alloc_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587358080,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:29",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_vcmd_ioasid_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594346611,
      "name": "vcmd_alloc_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588669760,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590142816,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:29",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_vcmd_ioasid_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142816,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```

```json
{
  "name": "vcmd_alloc_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590457136,
      "name": "vcmd_alloc_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:29",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590457136,
      "name": "vcmd_alloc_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
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
int vcmd_alloc_pasid(struct intel_iommu * iommu, unsigned int * pasid)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int * pasid</code> ➡️ <code>u32 * pasid</code>
</li>
</ul>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu * iommu, u32 * pasid)
```
</details>
</li>
</ul>
