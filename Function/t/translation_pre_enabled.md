# Function: <code>translation_pre_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:545",
      "file": "drivers/iommu/intel-iommu.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:552",
      "file": "drivers/iommu/intel-iommu.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:553",
      "file": "drivers/iommu/intel-iommu.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:554",
      "file": "drivers/iommu/intel-iommu.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602958483,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:270",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:527",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585335968,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603131119,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:270",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603137042,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:529",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577296,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604933949,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:273",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604941546,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:410",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702032,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605043991,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:258",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585968298,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:404",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929408,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605080789,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586113567,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:412",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072544,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609368774,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:259",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071586841890,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:416",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818256,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612440240,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:265",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071586912779,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:409",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876416,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614581216,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:262",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071586793291,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:418",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586756480,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615537100,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:263",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071587350139,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:400",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311584,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617342423,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:265",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/amd/init.c:init_iommu_one"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071588643049,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:333",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626320,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628070436,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:236",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one_late",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071590113593,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:308",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091728,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619836500,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:239",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one_late",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071590427433,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:308",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590404224,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622145236,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:234",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:init_iommu_one_late",
        "drivers/iommu/amd/init.c:init_iommu_one_late"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    },
    {
      "addr": 18446744071590771721,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:171",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_is_attach_deferred",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590747680,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604980412,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585873807,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:412",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833664,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604944713,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585733711,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:412",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585692704,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605061112,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063583,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:412",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022560,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```

```json
{
  "name": "translation_pre_enabled",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605084983,
      "name": "translation_pre_enabled",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:259",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586171711,
      "name": "translation_pre_enabled",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:412",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_add_device",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130512,
      "name": "translation_pre_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool translation_pre_enabled(struct amd_iommu * iommu)
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
