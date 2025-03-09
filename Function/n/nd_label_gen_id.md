# Function: <code>nd_label_gen_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584740672,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:246",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:__blk_label_update"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740672,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095031,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:246",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585092976,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585285592,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:246",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280560,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585371930,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:311",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365824,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799672,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:313",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793600,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586043820,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:322",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040128,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586183948,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:330",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178320,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586420967,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586416304,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586567735,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562960,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587352444,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587347360,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413983,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408880,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587295975,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587290816,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587862647,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857584,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
char * nd_label_gen_id(struct nd_label_id * label_id, const uuid_t * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589212670,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:332",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209008,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
char * nd_label_gen_id(struct nd_label_id * label_id, const uuid_t * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590768229,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:332",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590764544,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
char * nd_label_gen_id(struct nd_label_id * label_id, const uuid_t * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591109636,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:332",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591105984,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
char * nd_label_gen_id(struct nd_label_id * label_id, const uuid_t * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591454964,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:332",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591451312,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499457400,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499452552,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292719492,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292712336,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276679608,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276675494,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586258215,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253440,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586076583,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071808,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586515703,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586510928,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```

```json
{
  "name": "nd_label_gen_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586627447,
      "name": "nd_label_gen_id",
      "external": true,
      "loc": "drivers/nvdimm/label.c:324",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:__blk_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/namespace_devs.c:dpa_extents_show",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586622672,
      "name": "nd_label_gen_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 * uuid</code> ➡️ <code>const uuid_t * uuid</code>
</li>
</ul>
</details>
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
char * nd_label_gen_id(struct nd_label_id * label_id, u8 * uuid, u32 flags)
```
</details>
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
