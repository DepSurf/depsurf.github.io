# Function: <code>phy_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153920,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:318",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153920,
      "name": "phy_power_off",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450464,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:318",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450464,
      "name": "phy_power_off",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578208,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:318",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578208,
      "name": "phy_power_off",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583618144,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:318",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618144,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864240,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:318",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_off",
        "drivers/usb/host/ehci-platform.c:ehci_platform_power_on",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_off",
        "drivers/usb/host/ohci-platform.c:ohci_platform_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864240,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584064976,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:336",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064976,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584150080,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:336",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150080,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584340224,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341957,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584340192,
      "name": "phy_power_off",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584474896,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476645,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584474864,
      "name": "phy_power_off",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585139952,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141050,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585139920,
      "name": "phy_power_off",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585291232,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382485,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585291200,
      "name": "phy_power_off",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585175200,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324944,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585175168,
      "name": "phy_power_off",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585628960,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592346012,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585628928,
      "name": "phy_power_off",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:370",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207470,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071586788800,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587922448,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:370",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922448,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588196608,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:372",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588196608,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588488768,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:372",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588488768,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496477296,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496477296,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229790312,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_deinit_phys",
        "drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_enable_phy",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_disable_phy",
        "drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init",
        "drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe",
        "drivers/ata/libahci_platform.c:ahci_platform_disable_phys",
        "drivers/ata/libahci_platform.c:ahci_platform_enable_phys",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_remove",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_phy_enable",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_remove",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_phy_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229790312,
      "name": "phy_power_off",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290692464,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290692464,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275410148,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_enable_phy",
        "drivers/pci/controller/pcie-cadence.c:cdns_pcie_disable_phy",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275410148,
      "name": "phy_power_off",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443648,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445397,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584443616,
      "name": "phy_power_off",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584379328,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381077,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584379296,
      "name": "phy_power_off",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426560,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428309,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584426528,
      "name": "phy_power_off",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int phy_power_off(struct phy * phy)
```

```json
{
  "name": "phy_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532688,
      "name": "phy_power_off",
      "external": true,
      "loc": "drivers/phy/phy-core.c:332",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/phy.c:usb_phy_roothub_power_off",
        "drivers/usb/core/phy.c:usb_phy_roothub_power_on",
        "drivers/usb/core/phy.c:usb_phy_roothub_set_mode",
        "drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534437,
      "name": "phy_power_off.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584532656,
      "name": "phy_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
