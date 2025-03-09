# Function: <code>sysfs_create_bin_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581518688,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:480",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518688,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704688,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:486",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_sysfs_init",
        "drivers/acpi/sysfs.c:acpi_sysfs_table_handler",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704688,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792544,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:486",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792544,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581847616,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:488",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847616,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581997424,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:488",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:load_module",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997424,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582185328,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:534",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185328,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280464,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280464,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445363,
      "name": "sysfs_create_bin_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582445088,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544160,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544160,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850560,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:536",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efivars.c:create_efivars_bin_attributes",
        "drivers/firmware/efi/efivars.c:create_efivars_bin_attributes",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850560,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923616,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:537",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efivars.c:create_efivars_bin_attributes",
        "drivers/firmware/efi/efivars.c:create_efivars_bin_attributes",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923616,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951280,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:548",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951280,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286512,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:548",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:add_notes_attrs",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286512,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791872,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:558",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791872,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584411568,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:558",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411568,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640128,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:558",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_ccel_data_init",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640128,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584872416,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:571",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_populate_rootfs",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module/sysfs.c:add_notes_attrs",
        "kernel/bpf/btf.c:btf_module_notify",
        "kernel/bpf/sysfs_btf.c:btf_vmlinux_init",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/acpi/sysfs.c:acpi_ccel_data_init",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872416,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494182064,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/of/kobj.c:__of_add_property_sysfs",
        "drivers/of/fdt.c:of_fdt_raw_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494182064,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227618976,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/of/kobj.c:__of_add_property_sysfs",
        "drivers/of/fdt.c:of_fdt_raw_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227618976,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287869744,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_init",
        "arch/powerpc/platforms/powernv/opal-elog.c:elog_event",
        "arch/powerpc/platforms/powernv/opal-dump.c:process_dump",
        "arch/powerpc/platforms/powernv/opal-msglog.c:opal_msglog_sysfs_init",
        "arch/powerpc/platforms/powernv/ultravisor.c:__machine_initcall_powernv_uv_init",
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/of/kobj.c:__of_add_property_sysfs",
        "drivers/of/fdt.c:of_fdt_raw_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287869744,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273646758,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/of/kobj.c:__of_add_property_sysfs",
        "drivers/of/fdt.c:of_fdt_raw_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273646758,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512896,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512896,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450064,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450064,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503376,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503376,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int sysfs_create_bin_file(struct kobject * kobj, const struct bin_attribute * attr)
```

```json
{
  "name": "sysfs_create_bin_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583984,
      "name": "sysfs_create_bin_file",
      "external": true,
      "loc": "fs/sysfs/file.c:535",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ksysfs.c:ksysfs_init",
        "kernel/module.c:mod_sysfs_setup",
        "drivers/pci/pci-sysfs.c:pci_create_attr",
        "drivers/pci/vpd.c:pcie_vpd_create_sysfs_dev_files",
        "drivers/acpi/sysfs.c:acpi_bert_data_init",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/sfi/sfi_core.c:sfi_sysfs_install_table",
        "drivers/base/core.c:device_create_bin_file",
        "drivers/rtc/nvmem.c:rtc_nvmem_register",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583984,
      "name": "sysfs_create_bin_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
