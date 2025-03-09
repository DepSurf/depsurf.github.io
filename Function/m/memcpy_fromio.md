# Function: <code>memcpy_fromio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579098974,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595077928,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "arch/x86/platform/efi/efi-bgrt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687933,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583284382,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487840,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782103,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584252423,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_acpi.c:read_log"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584585850,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595317860,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595322548,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/firmware/efi/esrt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579098495,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801395,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583595326,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808139,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108119,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592471,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_acpi.c:read_log"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934206,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595503463,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595509660,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/firmware/efi/esrt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
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
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579096638,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865699,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583732510,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583947403,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256071,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584773838,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117598,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595756854,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:217",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcpy_fromio(void * dst, const volatile void * src, size_t count)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579088712,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910770,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771398,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998178,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335377,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584863067,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198846,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write",
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586725771,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:233",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725771,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcpy_fromio(void * buffer, const volatile void * addr, size_t size)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579099496,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009522,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584031222,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584214104,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584739638,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585282027,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/char/tpm/tpm_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627006,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write",
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587210075,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:987",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587210075,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void memcpy_fromio(void * buffer, const volatile void * addr, size_t size)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105023,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143158,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584228510,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584434222,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_write",
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584968252,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585519035,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/char/tpm/eventlog/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531239,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871338,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_write",
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510859,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1112",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587510859,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146848,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146848,
      "name": "memcpy_fromio",
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336912,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336912,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471584,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "fs/libfs.c:memory_read_from_io_buffer",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471584,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585035408,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585035408,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187472,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187472,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069360,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069360,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585516096,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516096,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586667728,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:88",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/sysfs.c:acpi_data_show",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667728,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587916304,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:93",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/sysfs.c:acpi_data_show",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916304,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588190336,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:93",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fb_io_fops.c:fb_io_read",
        "drivers/acpi/sysfs.c:acpi_data_show",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190336,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588482336,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:93",
      "file": "arch/x86/lib/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fb_io_fops.c:fb_io_read",
        "drivers/acpi/sysfs.c:acpi_data_show",
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/gpu/drm/drm_cache.c:memcpy_fallback",
        "drivers/gpu/drm/drm_cache.c:memcpy_fallback",
        "drivers/gpu/drm/drm_cache.c:memcpy_fallback",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482336,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227113480,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:memory_read_from_io_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3228399092,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "fs/pstore/ram_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pstore/ram_core.c:persistent_ram_save_old",
        "fs/pstore/ram_core.c:persistent_ram_save_old"
      ],
      "caller_func": []
    },
    {
      "addr": 3230173328,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 3230435156,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3230848448,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/dma/ti/edma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ti/edma.c:dma_ccerr_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3231750068,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3232339600,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/mtd/maps/map_funcs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/maps/map_funcs.c:simple_map_copy_from"
      ],
      "caller_func": []
    },
    {
      "addr": 3243927204,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 3234035120,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_fetch_response"
      ],
      "caller_func": []
    },
    {
      "addr": 3234351904,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/arm/include/asm/io.h:326",
      "file": "sound/core/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/memory.c:copy_to_user_fromio"
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
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286123392,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:58",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287142812,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:58",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:memory_read_from_io_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290985316,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:58",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291226552,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:58",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292428736,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "arch/powerpc/include/asm/io-defs.h:58",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
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
  "name": "memcpy_fromio",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1097",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275587664,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1097",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:pci_read_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276507204,
      "name": "memcpy_fromio",
      "external": false,
      "loc": "include/asm-generic/io.h:1097",
      "file": "drivers/misc/sram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/misc/sram.c:sram_read"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440336,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "fs/libfs.c:memory_read_from_io_buffer",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440336,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376016,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "fs/libfs.c:memory_read_from_io_buffer",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376016,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423248,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "fs/libfs.c:memory_read_from_io_buffer",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_process_event",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423248,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```

```json
{
  "name": "memcpy_fromio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529376,
      "name": "memcpy_fromio",
      "external": true,
      "loc": "arch/x86/lib/iomem.c:25",
      "file": "arch/x86/lib/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "mm/memory.c:generic_access_phys",
        "fs/libfs.c:memory_read_from_io_buffer",
        "drivers/pci/pci-sysfs.c:pci_read_rom",
        "drivers/video/fbdev/core/fbmem.c:fb_read",
        "drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys",
        "drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/char/tpm/tpm_crb.c:crb_recv",
        "drivers/misc/sram.c:sram_read",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529376,
      "name": "memcpy_fromio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void memcpy_fromio(void * dst, const volatile void * src, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * buffer</code>
</li>
<li>
<b>Param added. </b>
<code>const volatile void * addr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>void * dst</code>
</li>
<li>
<b>Param removed. </b>
<code>const volatile void * src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * to</code>
</li>
<li>
<b>Param added. </b>
<code>const volatile void * from</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>void * buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const volatile void * addr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void memcpy_fromio(void * to, const volatile void * from, size_t n)
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
