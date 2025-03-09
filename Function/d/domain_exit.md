# Function: <code>domain_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321792,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1912",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:disable_dmar_iommu",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321792,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668624,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1952",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:disable_dmar_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668624,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584854896,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1976",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854896,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584944080,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1981",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944080,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585370739,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1988",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365456,
      "name": "domain_exit.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585613011,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2016",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607984,
      "name": "domain_exit.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737475,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1902",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:device_notifier",
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726032,
      "name": "domain_exit.part.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585954512,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1893",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954512,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586097792,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1904",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097792,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586849312,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1919",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849312,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907104,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1976",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907104,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783696,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1982",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783696,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1978",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587340192,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071592474362,
      "name": "domain_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1871",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658128,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071594345001,
      "name": "domain_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1857",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125920,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596242788,
      "name": "domain_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1825",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590437904,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596771228,
      "name": "domain_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1774",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590785552,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071597679848,
      "name": "domain_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858912,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1904",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858912,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717936,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1904",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717936,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047808,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1904",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047808,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void domain_exit(struct dmar_domain * domain)
```

```json
{
  "name": "domain_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586156128,
      "name": "domain_exit",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1904",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_domain_free",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156128,
      "name": "domain_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void domain_exit(struct dmar_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void domain_exit(struct dmar_domain * domain)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void domain_exit(struct dmar_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void domain_exit(struct dmar_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void domain_exit(struct dmar_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void domain_exit(struct dmar_domain * domain)
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
