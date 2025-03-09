# Function: <code>swsusp_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702304,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1324",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702304,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722096,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1424",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722096,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749584,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1446",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749584,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745760,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1448",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745760,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779072,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1450",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779072,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812720,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1450",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812720,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859472,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1451",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859472,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893680,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1458",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893680,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943952,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1465",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943952,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988576,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1464",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988576,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973280,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1506",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973280,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975792,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1506",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975792,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1499",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592126325,
      "name": "swsusp_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580107120,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1503",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593896866,
      "name": "swsusp_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580246624,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1503",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595984511,
      "name": "swsusp_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580444768,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1555",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502546,
      "name": "swsusp_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580514768,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1598",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597400233,
      "name": "swsusp_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580575312,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225152488,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1465",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225152488,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911728,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1464",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911728,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850960,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1465",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850960,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904224,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1465",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904224,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void swsusp_free()
```

```json
{
  "name": "swsusp_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950288,
      "name": "swsusp_free",
      "external": true,
      "loc": "kernel/power/snapshot.c:1465",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:hibernate_preallocate_memory",
        "kernel/power/user.c:snapshot_ioctl",
        "kernel/power/user.c:snapshot_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950288,
      "name": "swsusp_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void swsusp_free()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void swsusp_free()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void swsusp_free()
```
</details>
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
