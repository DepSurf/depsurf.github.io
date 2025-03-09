# Function: <code>hub_ext_port_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153760,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:556",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153760,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546192,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:558",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546192,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585734416,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:561",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734416,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821632,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:570",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821632,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260896,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:570",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260896,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586518096,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:573",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518096,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666672,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:574",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666672,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:576",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920864,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071586947453,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587119312,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071587146189,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:580",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:wait_for_connected",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965616,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071587995187,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:580",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:wait_for_connected",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025376,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071591536985,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:587",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907328,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071591479199,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:587",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588516784,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071592556348,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:587",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589924464,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071594435756,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591503600,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:591",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591503600,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591925088,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:591",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591925088,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592664928,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:611",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592664928,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500192472,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500192472,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232673416,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232673416,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293478640,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293478640,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277120330,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277120330,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586825392,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071586852269,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586767168,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071586794477,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073872,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071587100749,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int hub_ext_port_status(struct usb_hub * hub, int port1, int type, u16 * status, u16 * change, u32 * ext_status)
```

```json
{
  "name": "hub_ext_port_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_ext_port_status",
      "external": false,
      "loc": "drivers/usb/core/hub.c:578",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181248,
      "name": "hub_ext_port_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071587207997,
      "name": "hub_ext_port_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
