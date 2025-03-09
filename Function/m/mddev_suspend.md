# Function: <code>mddev_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585730224,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:315",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:level_store"
      ],
      "caller_func": [
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730224,
      "name": "mddev_suspend.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071585730416,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586126976,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:308",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586126976,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586329744,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:321",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329744,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586425040,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:336",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586425040,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893632,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:359",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893632,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587180640,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:379",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180640,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587360832,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:370",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360832,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587632336,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:416",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632336,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587836160,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587836160,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688144,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:543",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688144,
      "name": "mddev_suspend.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071588688480,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588714944,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:539",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714944,
      "name": "mddev_suspend.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071588715280,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588600880,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:482",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600880,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589277744,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:483",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589277744,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590783978,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:488",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590754672,
      "name": "mddev_suspend.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071590755104,
      "name": "mddev_suspend",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592464074,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:480",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592433968,
      "name": "mddev_suspend.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071592434416,
      "name": "mddev_suspend",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592887470,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:set_bitmap_file",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev",
        "drivers/md/md.c:mddev_destroy_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592859440,
      "name": "mddev_suspend.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071592859936,
      "name": "mddev_suspend",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int mddev_suspend(struct mddev * mddev, bool interruptible)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593583696,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:448",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593583696,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501075400,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501075400,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233578464,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233578464,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294551696,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294551696,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277789040,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277789040,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587467136,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467136,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587235312,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235312,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587792304,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792304,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mddev_suspend(struct mddev * mddev)
```

```json
{
  "name": "mddev_suspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587912528,
      "name": "mddev_suspend",
      "external": true,
      "loc": "drivers/md/md.c:421",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587912528,
      "name": "mddev_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool interruptible</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
