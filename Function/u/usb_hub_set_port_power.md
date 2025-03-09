# Function: <code>usb_hub_set_port_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168400,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:770",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:usb_port_runtime_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168400,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560864,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:772",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560864,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748544,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:775",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748544,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585835664,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:784",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585835664,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586275024,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:784",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275024,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586532592,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:792",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532592,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586681392,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:793",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586681392,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586934944,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:820",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934944,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587133376,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133376,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587982912,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:824",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982912,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588042576,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:824",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042576,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587924528,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:831",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924528,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588534592,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:831",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588534592,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589942896,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:831",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942896,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591525792,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:835",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591525792,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591947680,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:835",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591947680,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int usb_hub_set_port_power(struct usb_device * hdev, struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592687472,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:855",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume",
        "drivers/usb/core/port.c:disable_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592687472,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500209632,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500209632,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232688880,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232688880,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293497792,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293497792,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277133478,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277133478,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586839456,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839456,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586781216,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781216,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587087936,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087936,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int usb_hub_set_port_power(struct usb_hub * hub, int port1, bool set)
```

```json
{
  "name": "usb_hub_set_port_power",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587195088,
      "name": "usb_hub_set_port_power",
      "external": true,
      "loc": "drivers/usb/core/hub.c:822",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/hub.c:hub_port_power_cycle",
        "drivers/usb/core/port.c:usb_port_runtime_suspend",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195088,
      "name": "usb_hub_set_port_power",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct usb_device * hdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>hdev, hub, port1, set</code> ➡️ <code>hub, port1, set</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct usb_device * hdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>hub, port1, set</code> ➡️ <code>hdev, hub, port1, set</code>
</li>
</ul>
</details>
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
