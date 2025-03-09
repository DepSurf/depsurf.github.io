# Function: <code>dm_table_get_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585814485,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1164",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818752,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213474,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1266",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212608,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586417981,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1267",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586417104,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586522306,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1318",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520880,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586989736,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1320",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988304,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587287462,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1358",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286016,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587467485,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1338",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466032,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587740865,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1351",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739328,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587945121,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943600,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797802,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1325",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_all_devices_attribute",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796288,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588815475,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1264",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814080,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588701750,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1460",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_construct_keyslot_manager",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700352,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589390406,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1455",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_construct_keyslot_manager",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388976,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590866844,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1447",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_supports_poll",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions",
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load",
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590865392,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
  "name": "dm_table_get_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592516990,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592520808,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-ima.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592539533,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592561456,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_postsuspend_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_undo_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_supports_poll",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592570433,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:retrieve_status"
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
  "name": "dm_table_get_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592947407,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592951198,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-ima.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592970633,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592991840,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_postsuspend_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_undo_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_supports_poll",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593000724,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:229",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:retrieve_status"
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
  "name": "dm_table_get_target",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593697231,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:232",
      "file": "drivers/md/dm-zone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-zone.c:dm_set_zones_restrictions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593701038,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:232",
      "file": "drivers/md/dm-ima.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ima.c:dm_ima_measure_on_table_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593720769,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:232",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_empty_flush",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593742368,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:232",
      "file": "drivers/md/dm-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_postsuspend_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_undo_targets",
        "drivers/md/dm-table.c:dm_table_presuspend_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:validate_hardware_zoned",
        "drivers/md/dm-table.c:validate_hardware_zoned",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_supports_poll",
        "drivers/md/dm-table.c:dm_table_construct_crypto_profile",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_alloc_md_mempools",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_table_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593752069,
      "name": "dm_table_get_target",
      "external": false,
      "loc": "drivers/md/dm-core.h:232",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-ioctl.c:retrieve_status"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501183948,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501182512,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233691140,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_all_devices_attribute",
        "drivers/md/dm-table.c:dm_table_supports_flush",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233689732,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294697440,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294695664,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277886956,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277885868,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587576097,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574576,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587344177,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342656,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901265,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899744,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
```

```json
{
  "name": "dm_table_get_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588016529,
      "name": "dm_table_get_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1349",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_has_no_data_devices",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588015008,
      "name": "dm_table_get_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct dm_target * dm_table_get_target(struct dm_table * t, unsigned int index)
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
