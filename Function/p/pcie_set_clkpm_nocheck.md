# Function: <code>pcie_set_clkpm_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331376,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:126",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:clk_ctl_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331376,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643120,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:126",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643120,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780736,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:126",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780736,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583822896,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:164",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583822896,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085936,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:153",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085936,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289648,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:152",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289648,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385040,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385040,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581968,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581968,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719200,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719200,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585372176,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585531584,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:142",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585409952,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:142",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585872000,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:142",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587065808,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:142",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588250880,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:143",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588527040,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:141",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588825984,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:144",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496978584,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496978584,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230242464,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230242464,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275646464,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275646464,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669680,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669680,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584598832,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584598832,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669360,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669360,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm_nocheck",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777056,
      "name": "pcie_set_clkpm_nocheck",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:150",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777056,
      "name": "pcie_set_clkpm_nocheck",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_set_clkpm_nocheck(struct pcie_link_state * link, int enable)
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
