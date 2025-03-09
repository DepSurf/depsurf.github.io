# Function: <code>iommu_device_register</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584879040,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:91",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879040,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298784,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:91",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298784,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585539376,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:91",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585539376,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662304,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:98",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662304,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585889584,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:83",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585889584,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586032272,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032272,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586767328,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:153",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767328,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586946896,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:155",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586946896,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828016,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:153",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828016,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388352,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:165",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388352,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588693920,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:167",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693920,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192144,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:213",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192144,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590513600,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:245",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590513600,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int iommu_device_register(struct iommu_device * iommu, const struct iommu_ops * ops, struct device * hwdev)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590869008,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:252",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590869008,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498833568,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/arm-smmu.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498833568,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231439184,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/iommu/omap-iommu.c:omap_iommu_probe",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_probe",
        "drivers/iommu/tegra-gart.c:tegra_gart_probe",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_probe",
        "drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe",
        "drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231439184,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292048144,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292048144,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793248,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793248,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585652432,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585652432,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982288,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982288,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int iommu_device_register(struct iommu_device * iommu)
```

```json
{
  "name": "iommu_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586090176,
      "name": "iommu_device_register",
      "external": true,
      "loc": "drivers/iommu/iommu.c:137",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586090176,
      "name": "iommu_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int iommu_device_register(struct iommu_device * iommu)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iommu_ops * ops</code>
</li>
<li>
<b>Param added. </b>
<code>struct device * hwdev</code>
</li>
</ul>
</details>
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
int iommu_device_register(struct iommu_device * iommu)
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
