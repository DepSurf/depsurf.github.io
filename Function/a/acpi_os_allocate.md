# Function: <code>acpi_os_allocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633838,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641104,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583645144,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071583654670,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660213,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669203,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672518,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583681876,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694992,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583717743,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719971,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583720557,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071583722058,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071583730299,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645144,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583720557,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583722058,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071583730299,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583956859,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583964182,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583969077,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071583979037,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984568,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992098,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995842,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005884,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019385,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584042144,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044263,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044872,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584046584,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584054602,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969077,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584044872,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584046584,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584054602,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584098529,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105813,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584110910,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584120433,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125964,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133494,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137290,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584147330,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161294,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584184578,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584186582,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584187147,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584188859,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584196966,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110910,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584187147,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584188859,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584196966,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165421,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584172698,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584177993,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584187557,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193089,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200618,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584204399,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584214585,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229623,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584252191,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254207,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254771,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584256476,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584264585,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177993,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584254771,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584256476,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584264585,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584462446,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584475147,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484241,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584505683,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584513200,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526655,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584533471,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584551697,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584575611,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584610700,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614051,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584615084,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584617006,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584631674,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071584648168,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648674,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584653763,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071584656592,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071584667474,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:84",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484241,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584615084,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584617006,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584631674,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584653763,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584656592,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584686571,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584699376,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584708668,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584730243,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737636,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751007,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584757799,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776277,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584800740,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584836484,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839831,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840864,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584842762,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584857323,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071584873827,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584874335,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584879414,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071584882630,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071584893594,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708668,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584840864,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584842762,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584857323,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584879414,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584882630,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786573,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799486,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584808768,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584829885,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837290,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584852575,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584867174,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584878312,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nseval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584903125,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584939841,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584943194,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944227,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071584946121,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071584960817,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071584977364,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584977872,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584982959,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071584986188,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071584997360,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584808768,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584944227,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584946121,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584960817,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584982959,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584986188,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989299,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585002275,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585011655,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585033488,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040955,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585056305,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070969,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585106176,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585142728,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585146128,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585147174,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585149090,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585163978,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071585180881,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585181410,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585186515,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071585189728,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071585200880,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011655,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585147174,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585149090,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585163978,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585186515,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585189728,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585125302,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138278,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585147740,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585169573,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585177040,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192390,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585207303,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585242534,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585279091,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585282491,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585283537,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585285452,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585300325,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071585317234,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585317763,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585322868,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071585326081,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071585337241,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147740,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585283537,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585285452,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585300325,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585322868,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585326081,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830245,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585843354,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585853105,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585874863,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882344,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585897764,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585913432,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585948355,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585985211,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988771,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989834,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585991718,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071586006783,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071586023770,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586024237,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586029437,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071586032662,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071586044416,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853105,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585989834,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585991718,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586006783,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586029437,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586032662,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585951209,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964505,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974253,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585995904,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ]
    },
    {
      "addr": 18446744071586003452,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586019100,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586035194,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586071269,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586107761,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ]
    },
    {
      "addr": 18446744071586111651,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586112697,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071586114564,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071586129612,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071586143538,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ]
    },
    {
      "addr": 18446744071586147004,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152187,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071586155483,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071586167454,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585974253,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585995904,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586107761,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586112697,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586114564,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586129612,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586143538,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586152187,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586155483,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585828381,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585841594,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851321,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585873014,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585880484,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896113,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585912211,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585948087,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585984887,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988440,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989486,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585991353,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071586006397,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071586023279,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586023724,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586028910,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071586032208,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071586044097,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851321,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585989486,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585991353,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586006397,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586028910,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586032208,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586314852,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328279,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338168,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071586360383,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586367949,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586383617,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586400290,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586436380,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586473959,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586477515,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478670,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071586480537,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071586496084,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071586513699,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586514144,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519442,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071586522861,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071586535857,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586338168,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586478670,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586480537,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586496084,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586519442,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071586522861,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587560464,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574667,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587585141,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071587607831,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string",
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ]
    },
    {
      "addr": 18446744071587615573,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587631504,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ]
    },
    {
      "addr": 18446744071587649584,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587686423,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ]
    },
    {
      "addr": 18446744071587726791,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ]
    },
    {
      "addr": 18446744071587730940,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587732146,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071587734187,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071587751044,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071587766583,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ]
    },
    {
      "addr": 18446744071587770378,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object"
      ]
    },
    {
      "addr": 18446744071587776260,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071587779723,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071587793483,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585141,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587607831,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587631504,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587686423,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587726791,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587732146,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587734187,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587751044,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587766583,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587770378,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587776260,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587779723,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588845046,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862266,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588875691,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588902937,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588911502,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930239,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952394,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998865,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589046973,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051687,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589053735,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589056446,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589077444,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101104,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101527,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589111984,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589113071,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589130272,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
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
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589134390,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589151690,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589165227,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589192857,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201636,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220239,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242362,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289409,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589338191,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589342919,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589344967,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589347640,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589369108,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392948,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589393399,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589403920,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589405016,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589422320,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
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
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589440358,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589457914,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589471595,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589499273,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508052,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589526751,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589548938,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589596177,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589645007,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589649735,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589651815,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654488,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589676068,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589700468,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589700919,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589711520,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589712616,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589730000,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497510952,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446603336497521744,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497527596,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497537080,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497543376,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497567876,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497594844,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497597504,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497598164,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446603336497604460,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446603336497614584,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497510952,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336497598164,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336497604460,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336497614584,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585032906,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040411,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585045924,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585055498,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061138,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069830,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078655,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099528,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585123666,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585125745,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585126310,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585127994,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585136408,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045924,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585126310,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585127994,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585136408,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584948514,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584955977,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584961479,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071584971043,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584976653,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584985322,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994076,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014002,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585038973,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585041047,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585041607,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585043219,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585051653,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071585092523,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_label_write"
      ],
      "caller_func": [
        "drivers/acpi/nfit/core.c:pkg_to_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961479,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585041607,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585043219,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585051653,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585083856,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585076886,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585089862,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099324,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585121157,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128624,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585143974,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585158887,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585194118,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585230675,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585234075,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235121,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585237036,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585251909,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071585268818,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269347,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585274452,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071585277665,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071585288825,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099324,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585235121,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585237036,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585251909,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585274452,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585277665,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void * acpi_os_allocate(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585183046,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evglock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585196022,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205484,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exconfig.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op"
      ]
    },
    {
      "addr": 18446744071585227317,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exnames.c:acpi_ex_allocate_name_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585234784,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585250134,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_buffer_to_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265047,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/hwpci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585300278,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585336835,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/tbutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbutils.c:acpi_tb_copy_dsdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340235,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utaddress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585341281,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utalloc.c:acpi_ut_initialize_buffer"
      ]
    },
    {
      "addr": 18446744071585343196,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    },
    {
      "addr": 18446744071585358069,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/utmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize"
      ]
    },
    {
      "addr": 18446744071585374978,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbcmds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375507,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585380612,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute"
      ]
    },
    {
      "addr": 18446744071585383825,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbhistry.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history",
        "drivers/acpi/acpica/dbhistry.c:acpi_db_add_to_history"
      ]
    },
    {
      "addr": 18446744071585394985,
      "name": "acpi_os_allocate",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:50",
      "file": "drivers/acpi/acpica/dbxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205484,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585341281,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585343196,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071585358069,
      "name": "acpi_os_allocate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585380612,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585383825,
      "name": "acpi_os_allocate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void * acpi_os_allocate(acpi_size size)
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
void * acpi_os_allocate(acpi_size size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * acpi_os_allocate(acpi_size size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * acpi_os_allocate(acpi_size size)
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
