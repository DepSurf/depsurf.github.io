# Function: <code>acpi_os_allocate_zeroed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583540334,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541440,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615414,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616840,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071583628157,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629909,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630823,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071583633135,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636536,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637673,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641353,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583644385,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651968,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660528,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669419,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676396,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583682980,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683849,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690932,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692418,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071583695743,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706277,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710493,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712896,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722579,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071583726389,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727214,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_SUB",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS"
      ]
    },
    {
      "addr": 18446744071583731670,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object"
      ]
    },
    {
      "addr": 18446744071583733294,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583736726,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616840,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583630823,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583692418,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583722579,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583727214,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583731670,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583861286,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583862408,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938497,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939929,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071583951233,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583952966,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583953880,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071583956149,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583959688,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583961285,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583964424,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583967460,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583975555,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984913,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992314,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584000123,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584007026,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008015,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584015672,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016792,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584020099,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584030670,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034911,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037315,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584046530,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584050869,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584051695,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584055916,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584057546,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060892,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939929,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583953880,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584016792,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584046530,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584051695,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584055916,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584000362,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584001484,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584080080,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584081512,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071584092745,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584094633,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584095551,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584097819,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101358,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584102955,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106055,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584109213,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116951,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584126309,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133710,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584141571,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584148472,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584149520,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584150595,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157600,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158760,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584162008,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584172828,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584177069,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584179473,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188805,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584193144,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584194058,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584197754,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584199384,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203103,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081512,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584095551,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584158760,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584188805,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584194058,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584197754,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049138,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584050737,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146840,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584148287,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071584159524,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161409,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162331,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584164711,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584168236,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584169844,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584172927,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584176230,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584184001,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193430,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200829,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208854,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584215746,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216808,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584217845,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224854,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226036,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584228773,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240586,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584244782,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247161,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256422,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584260776,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261690,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584265365,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584266714,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071584270709,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148287,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584162331,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584226036,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584256422,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584261690,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584265365,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584266714,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584314886,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317147,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584413602,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584427795,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431451,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437062,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584452776,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584456103,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457409,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584461369,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584467143,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584469993,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584475580,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584481850,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584499018,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584513617,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527078,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584539937,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584554002,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584556257,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584558327,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584569206,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571217,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584574761,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584593175,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584600287,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584604639,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616952,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584625525,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584627078,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584633684,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584636389,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071584642768,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584649184,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662968,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:89",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457409,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584571217,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584616952,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584627078,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584633684,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584636389,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534901,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584537395,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637031,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584651365,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655019,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584660938,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676803,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680103,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681575,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584685494,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584691311,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584694150,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584699809,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584706289,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584723617,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738069,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751432,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584764414,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778264,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779658,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071584783460,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794348,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584796358,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584799917,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584818929,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584826037,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830398,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584842708,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584851218,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584852771,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584859401,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584862106,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071584868469,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584874846,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584889036,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681575,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584779658,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584796358,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584842708,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584852771,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584859401,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584862106,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584632117,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634588,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584736137,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751012,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584754793,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584760729,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776776,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584780079,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584781586,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584785493,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791309,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584794250,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799919,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584806389,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823187,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837723,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853000,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584865210,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584880294,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584881711,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071584885517,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584896739,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584898749,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071584902300,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584921851,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584929393,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584933754,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584946067,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071584954732,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584956285,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071584962895,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071584965600,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071584971996,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584978370,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584992687,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781586,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584881711,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584898749,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584946067,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584956285,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584962895,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584965600,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584831813,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584833760,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071584937760,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071584948024,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584953393,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584957193,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584963225,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979367,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982718,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584984237,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584988207,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994073,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584997040,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585002714,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585009281,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585026756,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040718,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585056730,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068993,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071860,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585083486,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084921,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585088788,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099742,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585101738,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585105480,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585124524,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585132226,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585136616,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585149036,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585157866,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159420,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585166064,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585168797,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585175297,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585181909,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585196181,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833760,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584937760,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071584984237,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585040718,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585084921,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585101738,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585149036,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585159420,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585166064,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585168797,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584967541,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584969488,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585073568,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585083816,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585089189,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585092993,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099025,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585115231,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585118718,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585120237,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585124210,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130076,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585133043,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138717,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585145366,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585162841,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176803,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585192815,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205327,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585208194,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219837,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585221272,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585225139,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585236100,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585238096,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585241838,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585260886,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585268588,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585272978,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585285398,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585294228,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295782,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585302411,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585305144,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585311650,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585318262,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585332538,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969488,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585073568,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585120237,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585176803,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585221272,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585238096,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585285398,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585295782,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585302411,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585305144,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585663141,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665200,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585778752,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585787464,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ]
    },
    {
      "addr": 18446744071585793838,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585797419,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071585802630,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071585820033,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823521,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585825062,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585829153,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833839,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585838119,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585843793,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585850538,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585867309,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ]
    },
    {
      "addr": 18446744071585882107,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585898189,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585910882,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914041,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925643,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585927095,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585930964,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585940101,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446744071585943912,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585947569,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966774,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974523,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585979016,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585991766,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ]
    },
    {
      "addr": 18446744071586000708,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002279,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071586008911,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071586011673,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071586018123,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586024807,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586039577,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585665200,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585778752,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585787464,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585797419,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585802630,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585825062,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585867309,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585882107,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585927095,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585940101,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585943912,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585991766,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586002279,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586008911,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586011673,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788821,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585790464,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585897120,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585908320,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ]
    },
    {
      "addr": 18446744071585914694,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585918258,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071585923452,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071585940855,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585944343,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585945867,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585950117,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954849,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585959270,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964944,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971689,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988440,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ]
    },
    {
      "addr": 18446744071586003215,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071586006772,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586019525,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586032644,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047364,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586048799,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071586052668,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586063046,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446744071586066843,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071586070483,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586089675,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586097426,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586101902,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114612,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ipackage_to_ipackage",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ]
    },
    {
      "addr": 18446744071586123554,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125108,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071586131723,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071586134468,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071586140913,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586147574,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162621,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790464,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585897120,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585908320,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585918258,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585923452,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585945867,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585988440,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586003215,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586048799,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586063046,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586066843,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586114612,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586125108,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586131723,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586134468,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669189,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671805,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774359,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585786650,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585792038,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585795832,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585800702,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071585818122,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585821593,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823117,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585827289,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831994,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585836364,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585842033,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585848757,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585866274,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585880247,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585883789,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585896538,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585909665,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585924208,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925643,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585929511,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939894,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446744071585943664,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585947301,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966480,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974308,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978734,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585991401,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ]
    },
    {
      "addr": 18446744071586000330,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586001884,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071586008500,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071586011233,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071586017678,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586024302,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586039284,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800702,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585823117,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585880247,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585925643,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585939894,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585943664,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585991401,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586001884,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586008500,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586011233,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586148725,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586151381,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586257356,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271514,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586276926,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586281292,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586286388,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071586304253,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586308064,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586309588,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071586313760,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586318484,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586322854,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328718,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335604,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586353328,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586367712,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071586371254,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384042,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586397718,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412325,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586413760,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071586417684,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586428138,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446744071586431957,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071586435594,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454834,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462964,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586467390,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586480585,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ]
    },
    {
      "addr": 18446744071586489870,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491424,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071586498523,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071586501256,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071586508026,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586514722,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586530735,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286388,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586309588,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586367712,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586413760,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586428138,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586431957,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586480585,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586491424,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071586498523,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586501256,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587381365,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384160,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498602,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587514189,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ]
    },
    {
      "addr": 18446744071587520862,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587525063,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ]
    },
    {
      "addr": 18446744071587530815,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ]
    },
    {
      "addr": 18446744071587549448,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587553449,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555001,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071587559327,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587565656,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587567773,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ]
    },
    {
      "addr": 18446744071587575134,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587582383,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599772,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ]
    },
    {
      "addr": 18446744071587615338,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071587618949,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587631552,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ]
    },
    {
      "addr": 18446744071587646877,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587662334,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663851,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071587668044,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678997,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name"
      ]
    },
    {
      "addr": 18446744071587683146,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071587686471,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ]
    },
    {
      "addr": 18446744071587706688,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ]
    },
    {
      "addr": 18446744071587715196,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587718206,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ]
    },
    {
      "addr": 18446744071587734235,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ]
    },
    {
      "addr": 18446744071587744440,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587746147,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071587753668,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071587756557,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071587763856,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587770426,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ]
    },
    {
      "addr": 18446744071587788136,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514189,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587525063,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587530815,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587555001,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587567773,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587599772,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587615338,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587631552,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587663851,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587678997,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587683146,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587686471,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587706688,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587718206,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587734235,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587746147,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587753668,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587756557,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587770426,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588631589,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588638501,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588770991,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588790930,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588797260,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588802491,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588811363,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588831419,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588835070,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588839757,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843808,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588851259,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855978,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862784,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871319,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894590,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912073,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915665,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930805,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588949318,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588968151,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588971864,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588974889,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588990425,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995350,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588997962,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022144,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589032228,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589038084,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058675,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589069024,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072625,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589083161,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589084149,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589093541,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589102517,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123707,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
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
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588919333,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588926266,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589060250,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080370,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589086716,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091949,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589100737,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589120747,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124411,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589129101,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133152,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589140667,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589145386,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589152208,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589160759,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589184417,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589202352,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589205855,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220805,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239286,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589258231,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589261898,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265369,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589280936,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285846,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589288474,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589312960,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589323380,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589329254,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349987,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589360352,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589364289,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589374921,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589375909,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589385381,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589394389,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589415695,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
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
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589215557,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589221290,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589365610,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386066,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392412,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589397693,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589406481,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423728,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ]
    },
    {
      "addr": 18446744071589430235,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434973,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589439072,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589446683,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589451550,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589458480,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589467079,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490833,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508816,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589512319,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exregion.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527317,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545796,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589564855,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568570,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_normalize_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589572041,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589587656,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_internalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589592758,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589595242,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589619728,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589630148,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589636070,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589656835,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589667200,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589671201,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589682025,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589683013,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589692533,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589701957,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589721824,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589423728,
      "name": "acpi_os_allocate_zeroed.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071589721824,
      "name": "acpi_os_allocate_zeroed.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497381580,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497384472,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497484412,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497487720,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497489700,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497493724,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497502732,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497505808,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497507068,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ]
    },
    {
      "addr": 18446603336497517632,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497527484,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446603336497537380,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497542372,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497543884,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497550128,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497551312,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446603336497554040,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497560976,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446603336497563912,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446603336497567136,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497580768,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497585916,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497589456,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497604396,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446603336497609884,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497611164,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446603336497615640,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446603336497617416,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446603336497623644,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497507068,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336497527484,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336497551312,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336497560976,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336497563912,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336497604396,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336497611164,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336497615640,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336497617416,
      "name": "acpi_os_allocate_zeroed",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584916229,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917696,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585003056,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585009942,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585012862,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014566,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585018409,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585026630,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585028709,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585029815,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585032184,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585035745,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585037509,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040607,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044231,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585051778,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061043,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585070048,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077594,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585079186,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084590,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085483,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585087629,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094755,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585095902,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585098832,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585111351,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585116097,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585118825,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585127940,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585132478,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585133470,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585137226,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585138610,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585143451,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917696,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585003056,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585029815,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585061043,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585085483,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585095902,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585127940,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585133470,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585137226,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585138610,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584822149,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824263,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919065,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584925590,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584928505,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930204,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584934042,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584942258,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944332,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584945433,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071584947797,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584951348,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584953091,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584956170,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584959791,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584967328,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584976570,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071584985530,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993025,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584994602,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999996,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585000884,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585003025,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009033,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ]
    },
    {
      "addr": 18446744071585011256,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585014717,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585026673,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031414,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585034137,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585043752,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585047733,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048720,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585052885,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585053815,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585058646,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945433,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584976570,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585000884,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585009033,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585011256,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585043752,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585048720,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585052885,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585053815,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584919125,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584921072,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585025152,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585035400,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040773,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044577,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585050609,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585066815,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070302,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071821,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585075794,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585081660,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585084627,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090301,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585096950,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585114425,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128387,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585144399,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585156911,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159778,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585171421,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172856,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585176723,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187684,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189680,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585193422,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585212470,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585220172,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585224562,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585236982,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585245812,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247366,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585253995,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585256728,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585263234,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585269846,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585284122,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584921072,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585025152,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585071821,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585128387,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585172856,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585189680,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585236982,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585247366,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585253995,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585256728,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
```

```json
{
  "name": "acpi_os_allocate_zeroed",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585025269,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_create_semaphore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585027216,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_extract_package"
      ]
    },
    {
      "addr": 18446744071585131312,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/x86/apple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties"
      ]
    },
    {
      "addr": 18446744071585141560,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsfield.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585146933,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsmethod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585150737,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dsobject.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585156769,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172975,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dswstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dswstate.c:acpi_ds_create_walk_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585176462,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585177981,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeblk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block"
      ]
    },
    {
      "addr": 18446744071585181954,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evgpeutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187820,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evregion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585190787,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evrgnini.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585196461,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585203110,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585220585,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exfldio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exfldio.c:acpi_ex_insert_into_field"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585234547,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exoparg3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R"
      ]
    },
    {
      "addr": 18446744071585250559,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/exstorob.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exstorob.c:acpi_ex_store_string_to_string"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585263071,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265938,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsaccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585277581,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsinit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585279016,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsnames.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_get_normalized_pathname"
      ]
    },
    {
      "addr": 18446744071585282883,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585293844,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsutils.c:acpi_ns_externalize_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295840,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfeval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object"
      ]
    },
    {
      "addr": 18446744071585299582,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/nsxfname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/nsxfname.c:acpi_get_object_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585318630,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rscreate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rscreate.c:acpi_buffer_to_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326332,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/rsutils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330722,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/tbdata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/tbdata.c:acpi_tb_resize_root_table_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343142,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utcopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject"
      ]
    },
    {
      "addr": 18446744071585351972,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585353526,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utids.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    },
    {
      "addr": 18446744071585360155,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object"
      ]
    },
    {
      "addr": 18446744071585362888,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utosi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface",
        "drivers/acpi/acpica/utosi.c:acpi_ut_install_interface"
      ]
    },
    {
      "addr": 18446744071585369394,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/utxface.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585376006,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbconvert.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer",
        "drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390282,
      "name": "acpi_os_allocate_zeroed",
      "external": false,
      "loc": "include/acpi/platform/aclinuxex.h:55",
      "file": "drivers/acpi/acpica/dbnames.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027216,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585131312,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585177981,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585234547,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585279016,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585295840,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585343142,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585353526,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071585360155,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585362888,
      "name": "acpi_os_allocate_zeroed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * acpi_os_allocate_zeroed(acpi_size size)
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
void * acpi_os_allocate_zeroed(acpi_size size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * acpi_os_allocate_zeroed(acpi_size size)
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
