# Function: <code>phy_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583155216,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:247",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    },
    {
      "addr": 18446744071596344736,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1486",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596344736,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583155216,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451632,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:247",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    },
    {
      "addr": 18446744071596572877,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1728",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596572877,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583451632,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583579376,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:247",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    },
    {
      "addr": 18446744071597514339,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1904",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597514339,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583579376,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583617696,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:247",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    },
    {
      "addr": 18446744071598518375,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1909",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071598518375,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583617696,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583863792,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:247",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    },
    {
      "addr": 18446744071604888191,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1957",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604888191,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583863792,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584064544,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:265",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071605091165,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2002",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605091165,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584064544,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584149648,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:265",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607024001,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2361",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071607024001,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584149648,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584339864,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607175662,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2439",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341897,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071607175662,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584339808,
      "name": "phy_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584474536,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607236797,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476585,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071607236797,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584474480,
      "name": "phy_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585140420,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071611503447,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2906",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141124,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071611503447,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585140368,
      "name": "phy_exit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585291700,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071614617789,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3072",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382559,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071614617789,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585291648,
      "name": "phy_exit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585175396,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071616927862,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3118",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324980,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071616927862,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585175344,
      "name": "phy_exit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629156,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071617924755,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3250",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592346048,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071617924755,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585629104,
      "name": "phy_exit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586789043,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:283",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071619883620,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3288",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207506,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071619883620,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586788992,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587922688,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:283",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071632002256,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3294",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071632002256,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587922688,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588196848,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:285",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    },
    {
      "addr": 18446744071623887168,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3473",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071623887168,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071588196848,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588489008,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:285",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_resume",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable"
      ]
    },
    {
      "addr": 18446744071626360528,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:3569",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071626360528,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071588489008,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496476816,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446603336511365892,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511365892,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336496476816,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229789892,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_phys_put",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_phys_put",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_disable_phy",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 3244033276,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3244033276,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 3229789892,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290691776,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 13835058055302928960,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302928960,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 13835058055290691776,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275409760,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446743936271261294,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271261294,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936275409760,
      "name": "phy_exit",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443288,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607105806,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445337,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071607105806,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584443232,
      "name": "phy_exit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584378968,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init"
      ]
    },
    {
      "addr": 18446744071606910207,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381017,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071606910207,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584378912,
      "name": "phy_exit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426200,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607217107,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428249,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071607217107,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584426144,
      "name": "phy_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int phy_exit(struct phy * phy)
```

```json
{
  "name": "phy_exit",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532328,
      "name": "phy_exit",
      "external": true,
      "loc": "drivers/phy/phy-core.c:261",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_exit",
        "drivers/usb/core/phy.c:usb_phy_roothub_init",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    },
    {
      "addr": 18446744071607170805,
      "name": "phy_exit",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:2408",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534377,
      "name": "phy_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071607170805,
      "name": "phy_exit",
      "section": ".exit.text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584532272,
      "name": "phy_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
