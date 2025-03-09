# Function: <code>dm_table_get_num_targets</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585820304,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1534",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:retrieve_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820304,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213858,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1636",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214352,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586418365,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1637",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418848,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586522474,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1864",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523440,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586989943,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1854",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_get_wildcard_target"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990960,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587287441,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1942",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288880,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587467475,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1935",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587468928,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587740778,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1981",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742144,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587945034,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946400,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797724,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1957",
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
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588798976,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588815532,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1886",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588816960,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588701807,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:2083",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703328,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589390463,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:2079",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391968,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590866897,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:2070",
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
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590868304,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501183868,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501185096,
      "name": "dm_table_get_num_targets",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233691048,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233692224,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294697332,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294698976,
      "name": "dm_table_get_num_targets",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277886942,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277887960,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587576010,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587577376,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587344090,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587345456,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901178,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902544,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_num_targets",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588016442,
      "name": "dm_table_get_num_targets",
      "external": true,
      "loc": "drivers/md/dm-table.c:1979",
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
        "drivers/md/dm-table.c:dm_table_get_wildcard_target",
        "drivers/md/dm-table.c:dm_table_supports_dax"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588017808,
      "name": "dm_table_get_num_targets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
unsigned int dm_table_get_num_targets(struct dm_table * t)
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
