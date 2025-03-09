# Function: <code>ehci_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585363952,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:657",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071595298227,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:757",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363952,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2173
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585760560,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:669",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071595481297,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:757",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585760560,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950304,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:669",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071595734248,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950304,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586034208,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:669",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071596662147,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:755",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034208,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2121
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586478416,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071602992754,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586478416,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071603164518,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762422,
      "name": "ehci_setup.cold.87",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586742608,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071604970023,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920118,
      "name": "ehci_setup.cold.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586911024,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1972
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071605079116,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179743,
      "name": "ehci_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587176384,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1483
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071605118599,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379967,
      "name": "ehci_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587376816,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223808,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:657",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071609394470,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609394470,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071588223808,
      "name": "ehci_setup",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588260448,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:669",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071612465951,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612465951,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071588260448,
      "name": "ehci_setup",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588148032,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:669",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071614608615,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148032,
      "name": "ehci_setup",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785424,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:679",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071615565409,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615565409,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071588785424,
      "name": "ehci_setup",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590189040,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:679",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071617372001,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617372001,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 371
    },
    {
      "addr": 18446744071590189040,
      "name": "ehci_setup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591805568,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:679",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071628111296,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628111296,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071591805568,
      "name": "ehci_setup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592229120,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:679",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071619877840,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619877840,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071592229120,
      "name": "ehci_setup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592970240,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:679",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071622187520,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:751",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622187520,
      "name": "ehci_setup",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071592970240,
      "name": "ehci_setup",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500482344,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500482344,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232951580,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232951580,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1456
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293865952,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293865952,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2172
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277374870,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277374870,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071605016545,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587086047,
      "name": "ehci_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587082896,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ehci_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604982001,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071605099138,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334527,
      "name": "ehci_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587331376,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1483
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
int ehci_setup(struct usb_hcd * hcd)
```

```json
{
  "name": "ehci_setup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ehci_setup",
      "external": true,
      "loc": "drivers/usb/host/ehci-hcd.c:656",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_reset"
      ]
    },
    {
      "addr": 18446744071605122793,
      "name": "ehci_setup",
      "external": false,
      "loc": "drivers/usb/early/ehci-dbgp.c:756",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441007,
      "name": "ehci_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587437856,
      "name": "ehci_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1483
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int ehci_setup(struct usb_hcd * hcd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
