# Function: <code>board_added</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "board_added",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583365400,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:85",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "board_added",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583678644,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:85",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "board_added",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583816746,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:85",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "board_added",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583859722,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:85",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "board_added",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584123322,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:85",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int board_added(struct slot * p_slot)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584323856,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:71",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584336192,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336192,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584418912,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:54",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431440,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431440,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584615883,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:56",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627424,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584630607,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584752891,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584765120,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584768303,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ]
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443088,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071585444864,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071585456240,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071585459519,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ]
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585592416,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071591411120,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585603552,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071591413648,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585470951,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481968,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071591356027,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585937255,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948512,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    },
    {
      "addr": 18446744071592383969,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587140055,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152528,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
    },
    {
      "addr": 18446744071594247809,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343223,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359200,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071596210824,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588619303,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588635296,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
    },
    {
      "addr": 18446744071596735976,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588919479,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588935616,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
    },
    {
      "addr": 18446744071597644560,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497016612,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497029960,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497029960,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275676146,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275687552,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275687552,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584701707,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713936,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584717119,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584632475,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644704,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584647887,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703051,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715280,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584718463,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int board_added(struct controller * ctrl)
```

```json
{
  "name": "board_added",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584810699,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:59",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "board_added",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:229",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822864,
      "name": "board_added",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071584826047,
      "name": "board_added.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int board_added(struct slot * p_slot)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller * ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot * p_slot</code>
</li>
</ul>
</details>
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
int board_added(struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int board_added(struct controller * ctrl)
```
</details>
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
