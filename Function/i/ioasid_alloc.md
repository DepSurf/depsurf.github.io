# Function: <code>ioasid_alloc</code>

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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:304",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788420,
      "name": "ioasid_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586787568,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:305",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483309,
      "name": "ioasid_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586970416,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:305",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591426838,
      "name": "ioasid_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586852176,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:305",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/iommu-sva-lib.c:iommu_sva_alloc_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592484849,
      "name": "ioasid_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071587414160,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:304",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu-sva-lib.c:iommu_sva_alloc_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594353859,
      "name": "ioasid_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071588729456,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```

```json
{
  "name": "ioasid_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590214224,
      "name": "ioasid_alloc",
      "external": true,
      "loc": "drivers/iommu/ioasid.c:304",
      "file": "drivers/iommu/ioasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu-sva.c:iommu_sva_alloc_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590214224,
      "name": "ioasid_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
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
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set * set, ioasid_t min, ioasid_t max, void * private)
```
</details>
</li>
</ul>
