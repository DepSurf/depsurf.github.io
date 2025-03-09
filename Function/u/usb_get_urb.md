# Function: <code>usb_get_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202036,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:107",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_get_from_anchor"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204976,
      "name": "usb_get_urb",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597293,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:107",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597152,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585784861,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784720,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585871293,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868320,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586311837,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586311760,
      "name": "usb_get_urb",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586568989,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568416,
      "name": "usb_get_urb",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718205,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718128,
      "name": "usb_get_urb",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973344,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:109",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973264,
      "name": "usb_get_urb",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587172384,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587172304,
      "name": "usb_get_urb",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588022624,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:cancel_bulk_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022208,
      "name": "usb_get_urb",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588070085,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:cancel_bulk_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068672,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588069552,
      "name": "usb_get_urb",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587952597,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587951456,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071587952064,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588563237,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562096,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071588562704,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589974239,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589972704,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071589973552,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591567727,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:111",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591566032,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591566960,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591989471,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:111",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591987792,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591988704,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592729391,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:111",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592727712,
      "name": "usb_get_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071592728624,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500253088,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500248624,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232726624,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232723340,
      "name": "usb_get_urb",
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293546052,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293542016,
      "name": "usb_get_urb",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277166982,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277164240,
      "name": "usb_get_urb",
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
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586878464,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586878384,
      "name": "usb_get_urb",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586819584,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819504,
      "name": "usb_get_urb",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587126944,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587126864,
      "name": "usb_get_urb",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct urb * usb_get_urb(struct urb * urb)
```

```json
{
  "name": "usb_get_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234048,
      "name": "usb_get_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:110",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_get_from_anchor",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233968,
      "name": "usb_get_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
