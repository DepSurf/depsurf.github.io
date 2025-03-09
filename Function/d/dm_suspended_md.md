# Function: <code>dm_suspended_md</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792835,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:3457",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810832,
      "name": "dm_suspended_md",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586195057,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2460",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204480,
      "name": "dm_suspended_md",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586399537,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2520",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408944,
      "name": "dm_suspended_md",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586502897,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2732",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512416,
      "name": "dm_suspended_md",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970081,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979840,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587265121,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2900",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276640,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587445041,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2923",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456864,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715185,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2954",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730208,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587919393,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934560,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588770705,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:3011",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588786992,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588788604,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2858",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588805456,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588674396,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2877",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691152,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589362380,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2766",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379200,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590836956,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2947",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855024,
      "name": "dm_suspended_md",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592527212,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:3052",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592546640,
      "name": "dm_suspended_md",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592957788,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:3095",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592977888,
      "name": "dm_suspended_md",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593707612,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:3103",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593727872,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501150904,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501171176,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233665824,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233680288,
      "name": "dm_suspended_md",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294664024,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294682960,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277863714,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277877728,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587550369,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565536,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587318465,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333616,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587875537,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587890704,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int dm_suspended_md(struct mapped_device * md)
```

```json
{
  "name": "dm_suspended_md",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587991089,
      "name": "dm_suspended_md",
      "external": true,
      "loc": "drivers/md/dm.c:2959",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_suspended",
        "drivers/md/dm.c:dm_internal_resume_fast",
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_internal_suspend_noflush",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:dm_suspend",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-sysfs.c:dm_attr_suspended_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005968,
      "name": "dm_suspended_md",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
