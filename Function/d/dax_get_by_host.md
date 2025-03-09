# Function: <code>dax_get_by_host</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385936,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:482",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385936,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585815200,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:511",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815200,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062016,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:537",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062016,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586206432,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:536",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206432,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443632,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443632,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586591568,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591568,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377648,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:623",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377648,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587438384,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:631",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587438384,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321440,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:631",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321440,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888640,
      "name": "dax_get_by_host",
      "external": false,
      "loc": "drivers/dax/super.c:70",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888640,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499474480,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499474480,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231949660,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231949660,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292753088,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292753088,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276694812,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276694812,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282048,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282048,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119536,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119536,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539536,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539536,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
struct dax_device * dax_get_by_host(const char * host)
```

```json
{
  "name": "dax_get_by_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586651248,
      "name": "dax_get_by_host",
      "external": true,
      "loc": "drivers/dax/super.c:595",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_writeback_mapping_range",
        "drivers/dax/super.c:dax_visible",
        "drivers/dax/super.c:write_cache_store",
        "drivers/dax/super.c:write_cache_show",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/md/dm.c:dm_get_table_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651248,
      "name": "dax_get_by_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct dax_device * dax_get_by_host(const char * host)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct dax_device * dax_get_by_host(const char * host)
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
