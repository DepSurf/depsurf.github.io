# Function: <code>pcie_set_clkpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583331504,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:139",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state"
      ],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331504,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583644089,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:139",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583781705,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:139",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583824199,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:177",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584087239,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:166",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584290977,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:165",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584386943,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584583928,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584721561,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372128,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
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
      "addr": 18446744071585372128,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531536,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:155",
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
      "addr": 18446744071585531536,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585409904,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:155",
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
      "addr": 18446744071585409904,
      "name": "pcie_set_clkpm",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871952,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:155",
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
      "addr": 18446744071585871952,
      "name": "pcie_set_clkpm",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065760,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:155",
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
      "addr": 18446744071587065760,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588250832,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:156",
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
      "addr": 18446744071588250832,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588526992,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:154",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588526992,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588825936,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:157",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_enable_link_state",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825936,
      "name": "pcie_set_clkpm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496981052,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230244608,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275648704,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584672041,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584601193,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584671721,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_set_clkpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584779417,
      "name": "pcie_set_clkpm",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:163",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/pcie/aspm.c:pcie_aspm_set_policy",
        "drivers/pci/pcie/aspm.c:__pci_disable_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_powersave_config_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pcie_set_clkpm(struct pcie_link_state * link, int enable)
```
</details>
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
