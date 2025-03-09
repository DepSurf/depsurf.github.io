# Function: <code>hub_port_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158992,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:961",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158992,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551616,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:963",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551616,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738784,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4141",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738784,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826496,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4160",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826496,
      "name": "hub_port_disable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586265792,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4163",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265792,
      "name": "hub_port_disable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586523184,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4214",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523184,
      "name": "hub_port_disable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671792,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4276",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671792,
      "name": "hub_port_disable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4323",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586925920,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071586947844,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124368,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071587146580,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4385",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972448,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071587995581,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4403",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032208,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071591537379,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4523",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913632,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071591479593,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4527",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588523520,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071592556695,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4533",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589931488,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071594436155,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591512976,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4529",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591512976,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591934352,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4549",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591934352,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592674784,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4558",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592674784,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500200080,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500200080,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232678740,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232678740,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293485072,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293485072,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277123988,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277123988,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830448,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071586852660,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772208,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071586794868,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078928,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071587101140,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hub_port_disable(struct usb_hub * hub, int port1, int set_state)
```

```json
{
  "name": "hub_port_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hub_port_disable",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4371",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_disable",
        "drivers/usb/core/hub.c:usb_port_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587186080,
      "name": "hub_port_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071587208388,
      "name": "hub_port_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
