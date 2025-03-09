# Function: <code>enable_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353584,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:104",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583363088,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:157",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583374464,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:133",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583375904,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:483",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353584,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071583363088,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583374464,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071583375904,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666704,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:104",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583676336,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:157",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687792,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:133",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583688880,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:483",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666704,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071583676336,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583687792,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583688880,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583804928,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:104",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583814544,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:159",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583826080,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:133",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583827168,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:454",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804928,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071583814544,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583826080,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583827168,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847952,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:105",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583857504,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:159",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583868912,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:133",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583869984,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:454",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847952,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071583857504,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583868912,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071583869984,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111520,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:105",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584121088,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:159",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584132544,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:133",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584133616,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:454",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111520,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071584121088,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584132544,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584133616,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:91",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584321600,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_core.c:151",
      "file": "drivers/pci/hotplug/pciehp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584333152,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:193",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584348720,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584351952,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:465",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312192,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584315913,
      "name": "enable_slot.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071584321600,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584333152,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071584348720,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584351952,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584428560,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584443872,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584446768,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:465",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408096,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584411304,
      "name": "enable_slot.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584428560,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584443872,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584446768,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584640544,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584643424,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:465",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604288,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584607465,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584624864,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584626117,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584640544,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584643424,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584778224,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584781088,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742080,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584745257,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584762560,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584763813,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584778224,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584781088,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469600,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585472464,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:473",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432640,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071585435861,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585453840,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585455154,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585469600,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585472464,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585611472,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585614224,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:473",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585584368,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071591408655,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585601744,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591412875,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585611472,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585614224,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585489920,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585492672,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:473",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462912,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071591350921,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585480160,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591355254,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585489920,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585492672,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585956832,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585959488,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:473",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929168,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071592378291,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585946624,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071592383065,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585956832,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585959488,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587161392,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587164304,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:474",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131408,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071594242097,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587150512,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071594246901,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071587161392,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071587164304,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588331536,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588373808,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588377008,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:482",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331536,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588356256,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071596210693,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588373808,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071588377008,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588607632,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:158",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588649760,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:118",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588652976,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:482",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607632,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588632368,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071596735845,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588649760,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071588652976,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588907712,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:158",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588950160,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:117",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588953520,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:482",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907712,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071588932592,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071597644429,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588950160,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071588953520,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497004480,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497027032,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497043760,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497047056,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497004480,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336497027032,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446603336497043760,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446603336497047056,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291078720,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291078720,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275667100,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275685088,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275667100,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446743936275685088,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584727040,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584729840,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690896,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584694073,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584711376,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584712629,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584727040,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584729840,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584657808,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584660608,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621664,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584624841,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584642144,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584643397,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584657808,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584660608,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584728384,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584731248,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692240,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584695417,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584712720,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584713973,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584728384,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584731248,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```

```json
{
  "name": "enable_slot",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:71",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_core.c:159",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835952,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_core.c:119",
      "file": "drivers/pci/hotplug/acpiphp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584838816,
      "name": "enable_slot",
      "external": false,
      "loc": "drivers/pci/hotplug/acpiphp_glue.c:472",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799888,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071584803065,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584820304,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584821557,
      "name": "enable_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584835952,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584838816,
      "name": "enable_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int enable_slot(struct hotplug_slot * hotplug_slot)
```
</details>
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
