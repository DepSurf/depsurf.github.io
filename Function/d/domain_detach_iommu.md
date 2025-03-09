# Function: <code>domain_detach_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584321356,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1777",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584668167,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1817",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584854439,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1841",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584943654,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1846",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585365030,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1848",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585607567,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1876",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585725508,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585953536,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1753",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585953536,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586096752,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1764",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096752,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586848576,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1841",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848576,
      "name": "domain_detach_iommu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586906368,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1940",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_remove_dev",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586906368,
      "name": "domain_detach_iommu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586782976,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1946",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782976,
      "name": "domain_detach_iommu.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587338064,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1945",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587338064,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588657487,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1840",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590124944,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1826",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590124944,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590439456,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1794",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590439456,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590798912,
      "name": "domain_detach_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1744",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/nested.c:intel_nested_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590798912,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585857872,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1764",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857872,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585716896,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1764",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716896,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046768,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1764",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046768,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_detach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586154816,
      "name": "domain_detach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1764",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154816,
      "name": "domain_detach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
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
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int domain_detach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
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
