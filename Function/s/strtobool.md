# Function: <code>strtobool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int strtobool(const char * s, bool * res)
```

```json
{
  "name": "strtobool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981328,
      "name": "strtobool",
      "external": true,
      "loc": "lib/string.c:642",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bint",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:online_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981328,
      "name": "strtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595104443,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595136768,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510749,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333722,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_write_file_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583644268,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583926743,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584722556,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070060,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076876,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585580204,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585632252,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586539852,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595350252,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595379444,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531421,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424522,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_write_file_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583781884,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067766,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584912348,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585254860,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585263116,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585767852,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585819868,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721580,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:132",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596267797,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596296499,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519213,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508088,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_write_file_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583824636,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130726,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596622050,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584997628,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337180,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585346060,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386494,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585854572,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585906748,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586847980,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:147",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602583739,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602614314,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545405,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658661,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_write_file_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584087676,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584403302,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602952087,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/iommu/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_set_def_domain_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585419516,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765260,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774460,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585815950,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294428,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586347516,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335692,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:178",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602752423,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602782633,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572754,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602998539,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291452,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584626407,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585662300,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586011708,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586021324,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063102,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551805,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605181,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639036,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:179",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604546300,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604576828,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579609938,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604797360,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604806401,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584387164,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584725015,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585791980,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586150332,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586160444,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207518,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586700653,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586754045,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587767948,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:186",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604640385,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604671978,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634290,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604900641,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604909879,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584584140,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927383,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023260,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586385772,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586396668,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586443966,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587009456,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588072684,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604652673,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684458,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604830949,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:setup_bau"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659890,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604934516,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604943725,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584721469,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585063191,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586170972,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586533468,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586543308,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586591902,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587208944,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278492,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609003026,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609035471,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609168868,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:setup_bau"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579692658,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609249075,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609255784,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585372477,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585769431,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931148,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587315084,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327788,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377982,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588061408,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159260,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:194",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612067951,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612098877,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579670946,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612322093,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531885,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585888343,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587018300,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377020,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389564,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587438702,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588106800,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588487474,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:inhibited_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589156220,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614206258,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614211397,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:initramfs_async_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614238768,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677874,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614462302,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585410253,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765559,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586901932,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587258828,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587271676,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587322126,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587989488,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373218,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:inhibited_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589049932,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:188",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615123916,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615130141,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:initramfs_async_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615158919,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579756644,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615407817,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872397,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586248649,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463614,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587824862,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841166,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587889134,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588602546,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037346,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:inhibited_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770464,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616892596,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:initramfs_async_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616924396,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863240,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617200035,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587488477,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783394,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589176146,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589192178,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590015526,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590469894,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:inhibited_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591280436,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627483973,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:initramfs_async_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005288,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580712910,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590729282,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590746818,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591070610,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591088146,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/kstrtox.h:150",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510802384,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510820692,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:early_enable_pseudo_nmi",
        "arch/arm64/kernel/cpufeature.c:parse_kpti"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510830972,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:parse_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510842532,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "virt/kvm/arm/vgic/vgic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v3.c:early_gicv4_enable",
        "virt/kvm/arm/vgic/vgic-v3.c:early_common_trap_cfg",
        "virt/kvm/arm/vgic/vgic-v3.c:early_group1_trap_cfg",
        "virt/kvm/arm/vgic/vgic-v3.c:early_group0_trap_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490835296,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510974284,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510984488,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511067472,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511071928,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496980960,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497469080,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498967052,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499421456,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499432948,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499476500,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500294236,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511294632,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501749980,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243248012,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 3224865372,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 3243455908,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 3243464012,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 3243551536,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 3243554632,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 3230244516,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3231537140,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 3231950008,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3232763312,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3243953524,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234302316,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283670728,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302630048,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302641832,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292113968,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292665940,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292684320,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292754052,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293599888,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295193412,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271505686,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270699132,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270704812,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275648608,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276347378,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276649250,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276660084,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276695178,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277203014,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278153226,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604578945,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604610768,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636210,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604839976,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604849185,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584671949,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584992871,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931340,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223948,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586233788,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586282382,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586915024,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604570661,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579564514,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809037,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818237,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584601101,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584908455,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780476,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586042316,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586052156,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119870,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856192,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604656769,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688554,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579633474,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604917160,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604926369,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584671629,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014775,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120988,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586481436,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491276,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586539870,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163504,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588215548,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "strtobool",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604656769,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:set_debug_rodata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688510,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604835106,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:setup_bau"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667474,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "kernel/params.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604938687,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:early_page_poison_param"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604947896,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:parse_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779325,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585120951,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sysfs.c:force_remove_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229596,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593180,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:read_only_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603020,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:force_raw_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651582,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587270576,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588350844,
      "name": "strtobool",
      "external": false,
      "loc": "include/linux/string.h:193",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:enabled_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int strtobool(const char * s, bool * res)
```
</details>
</li>
</ul>
