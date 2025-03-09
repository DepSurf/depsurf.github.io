# Function: <code>cleanup_slots</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583354914,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:624",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583668054,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:624",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583806278,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:624",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583849526,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:625",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584113126,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:625",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313384,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:611",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333264,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:165",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333264,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584409338,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428656,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428656,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584605530,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624912,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624912,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584743322,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762608,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584762608,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585435642,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585454448,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454448,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585587386,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585602352,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602352,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465866,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480768,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480768,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585932106,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947248,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947248,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587134586,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587151184,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151184,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588336458,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357168,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588357168,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588612554,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588633280,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:129",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588633280,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588912682,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933552,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:129",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933552,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497005952,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497027152,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497027152,
      "name": "cleanup_slots",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cleanup_slots",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291080700,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275668824,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275685196,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275685196,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584692138,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584711424,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711424,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584622906,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584642192,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642192,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584693482,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712768,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584712768,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void cleanup_slots()
```

```json
{
  "name": "cleanup_slots",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584801130,
      "name": "cleanup_slots",
      "external": false,
      "loc": "drivers/pci/hotplug/cpci_hotplug_core.c:547",
      "file": "drivers/pci/hotplug/cpci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584820352,
      "name": "cleanup_slots",
      "external": true,
      "loc": "drivers/pci/hotplug/shpchp_core.c:130",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584820352,
      "name": "cleanup_slots",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cleanup_slots()
```
</details>
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
void cleanup_slots()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cleanup_slots()
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
