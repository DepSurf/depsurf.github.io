# Function: <code>bus_set_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584264944,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1005",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264944,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584606528,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:993",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606528,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584788336,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1144",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788336,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877456,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1194",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877456,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297184,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1195",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297184,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537808,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1196",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537808,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585657808,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1263",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585657808,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585887232,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1480",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585887232,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586029488,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029488,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586775488,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1818",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586775488,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586956608,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1848",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956608,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838400,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1869",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838400,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399536,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1884",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399536,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710080,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1821",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710080,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498827872,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498827872,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231437416,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_init",
        "drivers/iommu/omap-iommu.c:omap_iommu_init",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_init",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231437416,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292045648,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292045648,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585790464,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790464,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649648,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649648,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979504,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979504,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```

```json
{
  "name": "bus_set_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586087344,
      "name": "bus_set_iommu",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1536",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087344,
      "name": "bus_set_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bus_set_iommu(struct bus_type * bus, const struct iommu_ops * ops)
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
