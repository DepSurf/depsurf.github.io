# Function: <code>guid_equal</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584336932,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585358880,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371061,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585377262,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
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
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584408808,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584741198,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_do_proc",
        "drivers/acpi/apei/ghes.c:ghes_do_proc",
        "drivers/acpi/apei/ghes.c:ghes_do_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585787168,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585798789,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806318,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587230194,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:43",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584631240,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584970013,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586034014,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586046485,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586052461,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587531317,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071587538337,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531317,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587538337,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584732835,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585074334,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586173199,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586186613,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192669,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712165,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071587722369,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:44",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712165,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587722369,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183817,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935045,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585274092,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585278252,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586409517,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586423621,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429829,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587991256,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071588003041,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991256,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588003041,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186105,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070853,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585412044,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416188,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586556210,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586570421,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586576549,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588198616,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071588210609,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198616,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588210609,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579206587,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777131,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586121700,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125741,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587341251,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587355221,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360645,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589065425,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071589078556,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589065425,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589078556,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201979,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895547,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586241476,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245453,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587402979,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587416949,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587421899,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591608425,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071591612216,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608425,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591612216,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579204361,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585772413,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114893,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119905,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587284723,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_blk",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299013,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587303835,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591551707,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071591555430,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591551707,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591555430,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579240921,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586255389,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264507,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/prmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/prmt.c:find_guid_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586614829,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619857,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587865755,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872219,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592671202,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071592675251,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592671202,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592675251,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587495843,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507323,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/prmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/prmt.c:find_guid_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880275,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587884701,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589211878,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594556083,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071594560496,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594556083,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071594560496,
      "name": "guid_equal",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585373681,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "fs/efivarfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375971,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588767123,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781451,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/prmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/prmt.c:find_guid_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589227768,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589233145,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590767430,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592891802,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592906254,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
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
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585604177,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "fs/efivarfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585606803,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589056259,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589070875,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/prmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/prmt.c:find_guid_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589524402,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589529881,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591108847,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593330378,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593345086,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585849968,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "fs/efivarfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/inode.c:efivarfs_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853448,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589363123,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_enumerate_nondev_subnodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589376667,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/prmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/prmt.c:find_guid_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832434,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589838073,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591454175,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nsl_validate_type_guid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594087409,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594098766,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:46",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497475192,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497684672,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497690040,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499446584,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499459768,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499466864,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501554172,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501554172,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292703716,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292723296,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292732904,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
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
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276669584,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276681752,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276687436,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585000341,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586246690,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586260901,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267029,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119625,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915925,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585108272,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_nfit_ars_rescan",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_regions",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_regions",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_regions",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_region",
        "drivers/acpi/nfit/core.c:nfit_spa_is_virtual",
        "drivers/acpi/nfit/core.c:nfit_spa_is_virtual",
        "drivers/acpi/nfit/core.c:nfit_spa_is_virtual",
        "drivers/acpi/nfit/core.c:nfit_spa_is_virtual",
        "drivers/acpi/nfit/core.c:ars_start",
        "drivers/acpi/nfit/core.c:ars_start",
        "drivers/acpi/nfit/core.c:__nfit_mem_init",
        "drivers/acpi/nfit/core.c:__nfit_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585134508,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065058,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586079269,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085397,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587520472,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071587532353,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    },
    {
      "addr": 18446744071587557318,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:remove_id_store",
        "drivers/hv/vmbus_drv.c:hv_vmbus_get_id",
        "drivers/hv/vmbus_drv.c:hv_vmbus_get_id",
        "drivers/hv/vmbus_drv.c:hv_vmbus_dynid_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587571038,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "drivers/hv/channel_mgmt.c:vmbus_add_channel_work",
        "drivers/hv/channel_mgmt.c:vmbus_add_channel_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520472,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587532353,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186025,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022437,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585362444,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366588,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586504178,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586518389,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524517,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153144,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071588165089,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153144,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588165089,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```

```json
{
  "name": "guid_equal",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191273,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "arch/x86/kernel/cpu/mce/apei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/apei.c:apei_read_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128613,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469724,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader",
        "drivers/acpi/apei/erst.c:erst_reader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473916,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586615922,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630133,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass",
        "drivers/nvdimm/label.c:to_nvdimm_cclass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586636245,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588270552,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    },
    {
      "addr": 18446744071588282961,
      "name": "guid_equal",
      "external": false,
      "loc": "include/linux/uuid.h:36",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type",
        "drivers/firmware/efi/cper-x86.c:cper_get_err_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270552,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588282961,
      "name": "guid_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
bool guid_equal(const guid_t * u1, const guid_t * u2)
```
</details>
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
