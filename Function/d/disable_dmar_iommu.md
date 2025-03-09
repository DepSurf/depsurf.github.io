# Function: <code>disable_dmar_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322000,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1667",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322000,
      "name": "disable_dmar_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668880,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1706",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668880,
      "name": "disable_dmar_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584857389,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1720",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856336,
      "name": "disable_dmar_iommu.part.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946541,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1725",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945472,
      "name": "disable_dmar_iommu.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585367869,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1727",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366800,
      "name": "disable_dmar_iommu.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585610301,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1755",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609264,
      "name": "disable_dmar_iommu.part.66",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585734671,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1642",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726352,
      "name": "disable_dmar_iommu.part.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585963919,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1650",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954752,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586107231,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1661",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098032,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861646,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1706",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586849600,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071586849760,
      "name": "disable_dmar_iommu",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586915998,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1804",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907392,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071586907552,
      "name": "disable_dmar_iommu",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586796942,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1828",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783984,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071586784144,
      "name": "disable_dmar_iommu",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587353598,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1829",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587338896,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071587339056,
      "name": "disable_dmar_iommu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588667762,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1728",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658896,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590117840,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1696",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117840,
      "name": "disable_dmar_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590431360,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1667",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590431360,
      "name": "disable_dmar_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void disable_dmar_iommu(struct intel_iommu * iommu)
```

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590777392,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1617",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590777392,
      "name": "disable_dmar_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585867471,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1661",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859152,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585727375,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1661",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718176,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586057247,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1661",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586048048,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_dmar_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586165295,
      "name": "disable_dmar_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1661",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:dmar_iommu_hotplug",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156368,
      "name": "disable_dmar_iommu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void disable_dmar_iommu(struct intel_iommu * iommu)
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
