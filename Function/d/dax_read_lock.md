# Function: <code>dax_read_lock</code>

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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585385977,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:36",
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
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385168,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815241,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_iomap_pfn",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814368,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586062067,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060720,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586206483,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:37",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205136,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586443683,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586442320,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586591619,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590256,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587377699,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/md/dm-table.c:device_supports_dax"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376112,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587438435,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
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
      "addr": 18446744071587436800,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321491,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault",
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
      "addr": 18446744071587318576,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887517,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:49",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:dax_get_by_host"
      ],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_iomap_zero",
        "fs/dax.c:dax_iomap_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885808,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589237799,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:41",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_fault_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589236512,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590796005,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:45",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_file_unshare",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590794016,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591137541,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:45",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591135520,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591483237,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:45",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_holder_notify_failure",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ],
      "caller_func": [
        "fs/dax.c:dax_range_compare_iter",
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_unshare_iter",
        "fs/dax.c:dax_iomap_direct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481216,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499474544,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499473296,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231949720,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
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
      "addr": 3231947268,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292753200,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292750864,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276694862,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276693456,
      "name": "dax_read_lock",
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
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282099,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280736,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586119587,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn",
        "drivers/dax/device.c:dev_dax_huge_fault",
        "drivers/dax/device.c:dev_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118224,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539587,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538224,
      "name": "dax_read_lock",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int dax_read_lock()
```

```json
{
  "name": "dax_read_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586651299,
      "name": "dax_read_lock",
      "external": true,
      "loc": "drivers/dax/super.c:31",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_get_by_host",
        "drivers/dax/super.c:__bdev_dax_supported"
      ],
      "caller_func": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:dax_iomap_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586649952,
      "name": "dax_read_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int dax_read_lock()
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
