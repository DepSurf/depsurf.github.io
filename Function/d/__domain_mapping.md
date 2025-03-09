# Function: <code>__domain_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315632,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2133",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map",
        "drivers/iommu/intel-iommu.c:intel_iommu_map",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315632,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662448,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2177",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_map",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662448,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584848624,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2220",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_map",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848624,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584938608,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2228",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_map",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584938608,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585359872,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2227",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_map",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359872,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2255",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602912,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
    },
    {
      "addr": 18446744071585617098,
      "name": "__domain_mapping.cold.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2224",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728144,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
    },
    {
      "addr": 18446744071585741174,
      "name": "__domain_mapping.cold.93",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2212",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957952,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071585972980,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2223",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101248,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071586118582,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2239",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851184,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
    },
    {
      "addr": 18446744071586868726,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2298",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905008,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071591478750,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2339",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786704,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071591419362,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2331",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map_pages",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587343424,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    },
    {
      "addr": 18446744071592475218,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2223",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map_pages",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655904,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071594344701,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2183",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map_pages",
        "drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590129440,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071596243347,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot, gfp_t gfp)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2146",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map_pages",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590444592,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071596771589,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, long unsigned int phys_pfn, long unsigned int nr_pages, int prot, gfp_t gfp)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2060",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map_pages",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590791328,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
    },
    {
      "addr": 18446744071597680185,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2223",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585861936,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071585878940,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2223",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721392,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071585738726,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2223",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051264,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071586068598,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```

```json
{
  "name": "__domain_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2223",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159312,
      "name": "__domain_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071586176774,
      "name": "__domain_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct scatterlist * sg</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, iov_pfn, sg, phys_pfn, nr_pages, prot</code> ➡️ <code>domain, iov_pfn, phys_pfn, nr_pages, prot</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __domain_mapping(struct dmar_domain * domain, long unsigned int iov_pfn, struct scatterlist * sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot)
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
