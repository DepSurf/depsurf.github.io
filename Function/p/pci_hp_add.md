# Function: <code>pci_hp_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407911,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407911,
      "name": "pci_hp_add.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584406896,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584604107,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604107,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584603024,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584741895,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741895,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584740848,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432472,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585432000,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591408616,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585583936,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591350842,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585461888,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378171,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071585928128,
      "name": "pci_hp_add",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594241977,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587130272,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596210138,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588330240,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596735291,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588606336,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597643875,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588906416,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497003344,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497003344,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291077280,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291077280,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275666192,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275666192,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584690711,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690711,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584689664,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584621479,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621479,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584620432,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584692055,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692055,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584691008,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int pci_hp_add(struct hotplug_slot * slot)
```

```json
{
  "name": "pci_hp_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584799703,
      "name": "pci_hp_add",
      "external": true,
      "loc": "drivers/pci/hotplug/pci_hotplug_core.c:477",
      "file": "drivers/pci/hotplug/pci_hotplug_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register",
        "drivers/pci/hotplug/pciehp_core.c:pciehp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799703,
      "name": "pci_hp_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584798656,
      "name": "pci_hp_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int pci_hp_add(struct hotplug_slot * slot)
```
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
int pci_hp_add(struct hotplug_slot * slot)
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
