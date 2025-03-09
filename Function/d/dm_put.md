# Function: <code>dm_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792480,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2928",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close",
        "drivers/md/dm.c:rq_completed"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585792480,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586192366,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:1931",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190640,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586396478,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:1991",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586394768,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586499470,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2201",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496656,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966894,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2175",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964496,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587270510,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2364",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260176,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587451086,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2390",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440704,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587720946,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2421",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713088,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587928238,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587917392,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588780766,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2430",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588769104,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588799531,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2296",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788528,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588684379,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2315",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674320,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589368731,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2204",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589362304,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590838907,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2386",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590836880,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592528347,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2488",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592526048,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592958283,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2524",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956448,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593708107,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2532",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593706288,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501157148,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501152760,
      "name": "dm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233663192,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233662244,
      "name": "dm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294658544,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294656672,
      "name": "dm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277870966,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277860994,
      "name": "dm_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587559214,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548368,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587327294,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316464,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587884382,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587873536,
      "name": "dm_put",
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
void dm_put(struct mapped_device * md)
```

```json
{
  "name": "dm_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587989230,
      "name": "dm_put",
      "external": true,
      "loc": "drivers/md/dm.c:2426",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_blk_close"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_clear",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_set_geometry",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:__find_device_hash_cell",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dev_create",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/md/dm-sysfs.c:dm_attr_store",
        "drivers/md/dm-sysfs.c:dm_attr_show",
        "drivers/md/dm-rq.c:rq_completed",
        "drivers/md/dm-rq.c:rq_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988672,
      "name": "dm_put",
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
