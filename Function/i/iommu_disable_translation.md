# Function: <code>iommu_disable_translation</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308544,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1600",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:disable_dmar_iommu",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308544,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584654384,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1639",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:disable_dmar_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584654384,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840352,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1653",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840352,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930688,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1658",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930688,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585352128,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1660",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585352128,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1688",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595168,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585616843,
      "name": "iommu_disable_translation.cold.79",
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1565",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719360,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585740866,
      "name": "iommu_disable_translation.cold.82",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1576",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585946288,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071585971461,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1587",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586089696,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071586117131,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1628",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839136,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071586867701,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1726",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895360,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071591478059,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1750",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586774928,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071591418773,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1754",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330048,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071592473118,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1673",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644736,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071594342957,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115600,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1641",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115600,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590429040,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1612",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590429040,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590774752,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1562",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_shutdown",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:iommu_suspend",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:disable_dmar_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590774752,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1587",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850816,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071585877499,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1587",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709856,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071585737275,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1587",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039712,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071586067147,
      "name": "iommu_disable_translation.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```

```json
{
  "name": "iommu_disable_translation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_disable_translation",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1587",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:iommu_suspend",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147808,
      "name": "iommu_disable_translation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071586175323,
      "name": "iommu_disable_translation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_disable_translation(struct intel_iommu * iommu)
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
