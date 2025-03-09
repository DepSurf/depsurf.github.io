# Function: <code>dm_get_md_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585801184,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2575",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801184,
      "name": "dm_get_md_type.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071585806256,
      "name": "dm_get_md_type",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586201822,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:1747",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201744,
      "name": "dm_get_md_type",
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
unsigned int dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586406318,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:1804",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406240,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586509838,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2011",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509760,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586977374,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:1990",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586977312,
      "name": "dm_get_md_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587274023,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2175",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587273920,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587454359,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2215",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587454256,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587727655,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2246",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727552,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587932023,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931920,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588784744,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2247",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784656,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588803240,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2121",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588803152,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688840,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2140",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688752,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589369241,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2021",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377088,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590842555,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2201",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590852688,
      "name": "dm_get_md_type",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592533629,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2279",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592543376,
      "name": "dm_get_md_type",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592965245,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2325",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592974592,
      "name": "dm_get_md_type",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593715373,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2333",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593724576,
      "name": "dm_get_md_type",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501167920,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501167792,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233677640,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233677532,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294680068,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294679984,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277875708,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277875610,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587562999,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562896,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587331079,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330976,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587888167,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888064,
      "name": "dm_get_md_type",
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
enum dm_queue_mode dm_get_md_type(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588003463,
      "name": "dm_get_md_type",
      "external": true,
      "loc": "drivers/md/dm.c:2244",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_process_bio"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load",
        "drivers/md/dm-ioctl.c:table_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003360,
      "name": "dm_get_md_type",
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>enum dm_queue_mode</code>
</li>
</ul>
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
