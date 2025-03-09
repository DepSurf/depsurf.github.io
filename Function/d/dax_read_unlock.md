# Function: <code>dax_read_unlock</code>

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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386084,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:42",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385200,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815348,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:43",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_iomap_pfn",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814400,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586062164,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:43",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060752,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586206580,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:43",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205168,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586443784,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443584,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586591720,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586591408,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587377800,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377488,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587438536,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-table.c:device_not_dax_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587438224,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321592,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-table.c:device_not_dax_capable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587320000,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887714,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:55",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887152,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589237854,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:47",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236544,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590796090,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:51",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_file_unshare",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794064,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591137626,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:51",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135568,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591483322,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:51",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481264,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499474664,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499474168,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231949840,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231948700,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292753664,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292752960,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276695012,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276694588,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282200,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281888,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586119688,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/dax/device.c:dev_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119376,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539688,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539376,
      "name": "dax_read_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void dax_read_unlock(int id)
```

```json
{
  "name": "dax_read_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586651398,
      "name": "dax_read_unlock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586651200,
      "name": "dax_read_unlock",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void dax_read_unlock(int id)
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
