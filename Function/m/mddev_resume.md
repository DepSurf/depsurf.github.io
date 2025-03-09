# Function: <code>mddev_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585731440,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:327",
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
      "addr": 18446744071585731440,
      "name": "mddev_resume.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585731536,
      "name": "mddev_resume",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586150850,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:321",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586128240,
      "name": "mddev_resume.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586128336,
      "name": "mddev_resume",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586354933,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:334",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330800,
      "name": "mddev_resume.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586330896,
      "name": "mddev_resume",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586455120,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:350",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586429504,
      "name": "mddev_resume.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071586429600,
      "name": "mddev_resume",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586940658,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:378",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
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
      "addr": 18446744071586894800,
      "name": "mddev_resume.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071586894896,
      "name": "mddev_resume",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587231110,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:398",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
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
      "addr": 18446744071587182496,
      "name": "mddev_resume.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587182592,
      "name": "mddev_resume",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587411750,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:389",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
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
      "addr": 18446744071587362784,
      "name": "mddev_resume.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587362880,
      "name": "mddev_resume",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587684186,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:435",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587633632,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587633728,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587888466,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587837456,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587837552,
      "name": "mddev_resume",
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688544,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:564",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071588688544,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588715344,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:560",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071588715344,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588599824,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:503",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071588599824,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589276704,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:504",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071589276704,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590752256,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:509",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071590752256,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592429696,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:501",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:update_array_info",
        "drivers/md/md.c:set_bitmap_file",
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
      "addr": 18446744071592429696,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592887549,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:466",
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
      "addr": 18446744071592855120,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071592855296,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593663243,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:526",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:rdev_attr_store"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-autodetect.c:md_setup_drive",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592240,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501118884,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446603336501068592,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446603336501068744,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233635964,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 3233580264,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 3233580360,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294621848,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 13835058055294553680,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 13835058055294553840,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277839104,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446743936277790660,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446743936277790756,
      "name": "mddev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587519442,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587468432,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587468528,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587287602,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587236608,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587236704,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587844610,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587793600,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587793696,
      "name": "mddev_resume",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mddev_resume(struct mddev * mddev)
```

```json
{
  "name": "mddev_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587959015,
      "name": "mddev_resume",
      "external": true,
      "loc": "drivers/md/md.c:440",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:add_bound_rdev"
      ],
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
      "addr": 18446744071587913808,
      "name": "mddev_resume.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071587913904,
      "name": "mddev_resume",
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
