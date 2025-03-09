# Function: <code>usb_free_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585204397,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:90",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204736,
      "name": "usb_free_urb",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597447,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:90",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597120,
      "name": "usb_free_urb",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585785015,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784688,
      "name": "usb_free_urb",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868720,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868720,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586311943,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586311984,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586569095,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568448,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718311,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718352,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973447,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:92",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973504,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587172487,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587172544,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588021524,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:cancel_bulk_urbs",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021680,
      "name": "usb_free_urb",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588069089,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:cancel_bulk_urbs",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070512,
      "name": "usb_free_urb",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587951873,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587952768,
      "name": "usb_free_urb",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588562513,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563408,
      "name": "usb_free_urb",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589974535,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589973696,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071589974672,
      "name": "usb_free_urb",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591568039,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:94",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591567120,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071591568192,
      "name": "usb_free_urb",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591989783,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:94",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591988864,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071591989936,
      "name": "usb_free_urb",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592729703,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:94",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592728784,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071592729856,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500253256,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500250472,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446603336500250568,
      "name": "usb_free_urb",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232726716,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232725284,
      "name": "usb_free_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3232725356,
      "name": "usb_free_urb",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293542768,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293542768,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277167058,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277164840,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586878567,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586878624,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586819687,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819744,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587127047,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127104,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void usb_free_urb(struct urb * urb)
```

```json
{
  "name": "usb_free_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234151,
      "name": "usb_free_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:93",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_disconnect",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:usb_hcd_flush_endpoint",
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/message.c:sg_clean",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:destroy_async",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234208,
      "name": "usb_free_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
