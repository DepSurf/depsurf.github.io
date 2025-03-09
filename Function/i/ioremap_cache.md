# Function: <code>ioremap_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579286880,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:313",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/memremap.c:memremap",
        "kernel/memremap.c:memremap",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286880,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579286968,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:312",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/memremap.c:memremap",
        "kernel/memremap.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286544,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579302360,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:312",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/memremap.c:memremap",
        "kernel/memremap.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301936,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300088,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:313",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/memremap.c:memremap",
        "kernel/memremap.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299680,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320400,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:365",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/memremap.c:memremap",
        "kernel/memremap.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320400,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331168,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:365",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:copy_oldmem_page",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331168,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579357424,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:373",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579357424,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371584,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:393",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371584,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376192,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376192,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404784,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:pcc_parse_subspace_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404784,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405360,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:pcc_parse_subspace_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405360,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408592,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:417",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408592,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471216,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:417",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471216,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548544,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:422",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548544,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653584,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:429",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653584,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667808,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:434",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667808,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702368,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:434",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/crash_dump_64.c:__copy_oldmem_page",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702368,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * ioremap_cache(phys_addr_t phys_addr, size_t size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490344280,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/arm64/mm/ioremap.c:85",
      "file": "arch/arm64/mm/ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_prepare",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/meson/meson_sm.c:meson_sm_map_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490344280,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * ioremap_cache(resource_size_t offset, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272512442,
      "name": "ioremap_cache",
      "external": true,
      "loc": "kernel/iomem.c:9",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272512442,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 50
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372096,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372096,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302288,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302288,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372016,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372016,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380496,
      "name": "ioremap_cache",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:415",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/nvs.c:suspend_nvs_save",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/acpi/apei/bert.c:bert_init",
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380496,
      "name": "ioremap_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>resource_size_t phys_addr</code> ➡️ <code>phys_addr_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * ioremap_cache(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>resource_size_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
</ul>
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
