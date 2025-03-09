# Function: <code>device_to_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584306320,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:875",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584306320,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652992,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:882",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652992,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839024,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:883",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839024,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584928736,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:888",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584928736,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350112,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:861",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350112,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585593072,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:863",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585593072,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717328,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:739",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:set_domain_for_dev",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717328,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585949104,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:751",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949104,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586092320,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092320,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586841312,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:782",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841312,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:865",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480016,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586910048,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:881",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420498,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586790128,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:887",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592476600,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587346832,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:734",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594346226,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588661024,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:710",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/svm.c:intel_svm_page_response"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596243567,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590134272,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 838
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "device_to_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:710",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/svm.c:intel_svm_page_response"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596771804,
      "name": "device_to_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590448064,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853440,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853440,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585712480,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585712480,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042336,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042336,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```

```json
{
  "name": "device_to_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586150096,
      "name": "device_to_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:762",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel-iommu.c:intel_svm_device_to_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_remove_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:prepare_domain_attach_device",
        "drivers/iommu/intel-iommu.c:domain_add_dev_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150096,
      "name": "device_to_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
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
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct intel_iommu * device_to_iommu(struct device * dev, u8 * bus, u8 * devfn)
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
