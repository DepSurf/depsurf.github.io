# Function: <code>iommu_flush_write_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308384,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1330",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308384,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584654176,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1337",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584654176,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840144,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1351",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840144,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946969,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1356",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935344,
      "name": "iommu_flush_write_buffer.part.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368297,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1339",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356576,
      "name": "iommu_flush_write_buffer.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1341",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594976,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071585616831,
      "name": "iommu_flush_write_buffer.cold.78",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1217",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741699,
      "name": "iommu_flush_write_buffer.cold.97",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585731888,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1222",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585973275,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585961200,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1233",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118812,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586104512,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1249",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_iommu_hw",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870127,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586858416,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1332",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_iommu_hw",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480244,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586912832,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1356",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420718,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586793344,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1360",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477020,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587350192,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1290",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594346290,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588662464,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590136048,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1245",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590136048,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590449872,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1244",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590449872,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590794896,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1104",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794896,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1233",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585879170,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585865200,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1233",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738956,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585724656,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1233",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068828,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586054528,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_flush_write_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_flush_write_buffer",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:1233",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177004,
      "name": "iommu_flush_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586162576,
      "name": "iommu_flush_write_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```
</details>
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
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu * iommu)
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
