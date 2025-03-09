# Function: <code>acpi_os_acquire_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540693,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1703",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540693,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861667,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1509",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861667,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000743,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1504",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_dispatch",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000743,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049536,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1503",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049536,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315856,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1513",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status",
        "drivers/acpi/acpica/hwxface.c:acpi_write_bit_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315856,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535904,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1588",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535904,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633120,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1594",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633120,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584832832,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1580",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584832832,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968560,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968560,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664160,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664160,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585789840,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1619",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_install_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585789840,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670192,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1609",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670192,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149792,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1604",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149792,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382528,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1521",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382528,
      "name": "acpi_os_acquire_lock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632896,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1521",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632896,
      "name": "acpi_os_acquire_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920640,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1521",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920640,
      "name": "acpi_os_acquire_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216912,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1515",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_remove_sci_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216912,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497382216,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497382216,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916640,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916640,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822560,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822560,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920144,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920144,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```

```json
{
  "name": "acpi_os_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026288,
      "name": "acpi_os_acquire_lock",
      "external": true,
      "loc": "drivers/acpi/osl.c:1600",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_enable_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block",
        "drivers/acpi/acpica/evgpeblk.c:acpi_ev_delete_gpe_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_walk_gpe_list",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock",
        "drivers/acpi/acpica/evglock.c:acpi_ev_global_lock_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers",
        "drivers/acpi/acpica/evxface.c:acpi_install_sci_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_finish_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_status",
        "drivers/acpi/acpica/evxfgpe.c:acpi_clear_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe_wake_mask",
        "drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mark_gpe_for_wake",
        "drivers/acpi/acpica/evxfgpe.c:acpi_mask_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_disable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe",
        "drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026288,
      "name": "acpi_os_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int acpi_os_acquire_lock(spinlock_t * lockp)
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
