# Function: <code>pcie_config_aspm_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331008,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:430",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331008,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642752,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:430",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642752,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780368,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:444",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780368,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823136,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:689",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823136,
      "name": "pcie_config_aspm_link",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086176,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:719",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086176,
      "name": "pcie_config_aspm_link",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289888,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:744",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289888,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385280,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:742",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385280,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582208,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:757",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:link_state_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582208,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719440,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719440,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585376192,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:752",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585376192,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585533872,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:744",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533872,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585412688,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:744",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412688,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874912,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:744",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874912,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068592,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:780",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068592,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588253936,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588253936,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588529280,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:722",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529280,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588826352,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:723",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_pm_state_change",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826352,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496978864,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496978864,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230242704,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230242704,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275646694,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275646694,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669920,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669920,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599072,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599072,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669600,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669600,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
```

```json
{
  "name": "pcie_config_aspm_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777296,
      "name": "pcie_config_aspm_link",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:761",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_exit_link_state",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777296,
      "name": "pcie_config_aspm_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_config_aspm_link(struct pcie_link_state * link, u32 state)
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
