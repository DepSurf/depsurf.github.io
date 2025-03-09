# Function: <code>usb_disable_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211200,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1063",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_disable_interface",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211200,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585604320,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1060",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604320,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585791888,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1063",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791888,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585878384,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1061",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878384,
      "name": "usb_disable_endpoint",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586318848,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1100",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586318848,
      "name": "usb_disable_endpoint",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576400,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1125",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576400,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725360,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1126",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725360,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980128,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980128,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179168,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179168,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588029504,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1136",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029504,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588079456,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1277",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079456,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587962256,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1283",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962256,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588573136,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1283",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588573136,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589984448,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1283",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589984448,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591578800,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1284",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591578800,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592000560,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1279",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592000560,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592740624,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1280",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints",
        "drivers/usb/core/message.c:usb_disable_device_endpoints"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592740624,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500261976,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500261976,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232733832,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232733832,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293558288,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293558288,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277175168,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277175168,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885248,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885248,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826368,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826368,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587133728,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133728,
      "name": "usb_disable_endpoint",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device * dev, unsigned int epaddr, bool reset_hardware)
```

```json
{
  "name": "usb_disable_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587240816,
      "name": "usb_disable_endpoint",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/hub.c:usb_ep0_reinit",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/message.c:usb_disable_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240816,
      "name": "usb_disable_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
