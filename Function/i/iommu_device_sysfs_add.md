# Function: <code>iommu_device_sysfs_add</code>

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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884320,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:57",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071584884320,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304128,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:57",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585304128,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545072,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:57",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585545072,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669472,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:57",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585669472,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585896624,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585896624,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039456,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071586039456,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586780928,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071586780928,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961712,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071586961712,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586843504,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071586843504,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587404656,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071587404656,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588716080,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071588716080,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198912,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071590198912,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590520400,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071590520400,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590875264,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071590875264,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498841488,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446603336498841488,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231446844,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 3231446844,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292059328,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292059328,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585800432,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585800432,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585659616,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585659616,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989472,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071585989472,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
```

```json
{
  "name": "iommu_device_sysfs_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586097392,
      "name": "iommu_device_sysfs_add",
      "external": true,
      "loc": "drivers/iommu/iommu-sysfs.c:54",
      "file": "drivers/iommu/iommu-sysfs.c",
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
      "addr": 18446744071586097392,
      "name": "iommu_device_sysfs_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
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
int iommu_device_sysfs_add(struct iommu_device * iommu, struct device * parent, const struct attribute_group * * groups, const char * fmt, void (anon))
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
