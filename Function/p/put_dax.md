# Function: <code>put_dax</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386572,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:470",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/inode.c:ext4_iomap_end",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385904,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816028,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:499",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815168,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586063144,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:525",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060832,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207560,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:524",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205248,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586444007,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442400,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586591943,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590336,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587378023,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:611",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376192,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587438743,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:619",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436880,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587322167,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:619",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318656,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587889201,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:606",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885888,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589237056,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:415",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589237056,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590795257,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:467",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:fs_put_dax"
      ],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590795136,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591136793,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:470",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:fs_put_dax"
      ],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136672,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591482489,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:471",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:fs_put_dax"
      ],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591482368,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499476548,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499473416,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231950048,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231948012,
      "name": "put_dax",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292754140,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292751808,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276695234,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276693498,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282423,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280816,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586119911,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/nvdimm/pmem.c:pmem_release_disk",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118304,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539911,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538304,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```

```json
{
  "name": "put_dax",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586651623,
      "name": "put_dax",
      "external": true,
      "loc": "drivers/dax/super.c:583",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "drivers/dax/bus.c:dev_dax_release",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_put_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650560,
      "name": "put_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void put_dax(struct dax_device * dax_dev)
```
</details>
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
