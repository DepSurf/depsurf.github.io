# Function: <code>device_bind_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584397536,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:264",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397536,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584732640,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:311",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732640,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584921952,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:307",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584921952,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585006896,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:308",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585006896,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585428992,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:336",
      "file": "drivers/base/dd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428992,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585671920,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:358",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671920,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585802032,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:423",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802032,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586034912,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034912,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586182320,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182320,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586945228,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:435",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:serio_bind_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943744,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587031292,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:458",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:serio_bind_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029168,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586915068,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:475",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586912832,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587477224,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:477",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587474688,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797570,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:491",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795088,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590294786,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:496",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590291152,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590615033,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:495",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590611520,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590974137,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:495",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:__device_attach",
        "drivers/base/dd.c:__device_attach"
      ],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590970624,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498980288,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498980288,
      "name": "device_bind_driver",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231549072,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231549072,
      "name": "device_bind_driver",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292131120,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292131120,
      "name": "device_bind_driver",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276358162,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276358162,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585942688,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942688,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585791776,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791776,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586132336,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132336,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int device_bind_driver(struct device * dev)
```

```json
{
  "name": "device_bind_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586240928,
      "name": "device_bind_driver",
      "external": true,
      "loc": "drivers/base/dd.c:466",
      "file": "drivers/base/dd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/card.c:pnp_request_card_device",
        "drivers/base/dd.c:__device_attach",
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/usb/core/driver.c:usb_driver_claim_interface",
        "drivers/input/serio/serio.c:drvctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240928,
      "name": "device_bind_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
