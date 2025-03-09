# Function: <code>dm_device_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792448,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2865",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_any_congested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792448,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196677,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:1868",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190608,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401172,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:1925",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586394736,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586505018,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2135",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496624,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972064,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2109",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964464,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587266538,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2299",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260144,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446828,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2328",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440672,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587716672,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2359",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713056,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587920960,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917360,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588775062,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2366",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:clone_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588769072,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797512,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2232",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:clone_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788496,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588676488,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2251",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674288,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589366501,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2141",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362272,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590846025,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2323",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590836848,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592533037,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2425",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592526000,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592964653,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2461",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956400,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593714781,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2469",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:validate_hardware_zoned",
        "drivers/md/dm-table.c:validate_hardware_zoned",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706240,
      "name": "dm_device_name",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501158688,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501149728,
      "name": "dm_device_name",
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233666768,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:validate_hardware_logical_block_alignment",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233662216,
      "name": "dm_device_name",
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294665184,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294656656,
      "name": "dm_device_name",
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277864552,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277860958,
      "name": "dm_device_name",
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587551936,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548336,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587320032,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316432,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587877104,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873504,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
const char * dm_device_name(struct mapped_device * md)
```

```json
{
  "name": "dm_device_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587992656,
      "name": "dm_device_name",
      "external": true,
      "loc": "drivers/md/dm.c:2363",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_device_name",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_table_resume_targets",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_calculate_queue_limits",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_get_integrity_disk",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_table_add_target",
        "drivers/md/dm-table.c:dm_put_device",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_table_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988640,
      "name": "dm_device_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
