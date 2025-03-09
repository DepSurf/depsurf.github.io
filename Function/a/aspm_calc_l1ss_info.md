# Function: <code>aspm_calc_l1ss_info</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583827976,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:440",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584091004,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:455",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584295176,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:480",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584390436,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:478",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584586536,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:493",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584723543,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state * link, struct aspm_register_info * upreg, struct aspm_register_info * dwreg)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585374160,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071585380404,
      "name": "aspm_calc_l1ss_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:452",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536608,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1027
    },
    {
      "addr": 18446744071591399444,
      "name": "aspm_calc_l1ss_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:452",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414704,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    },
    {
      "addr": 18446744071591341645,
      "name": "aspm_calc_l1ss_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:452",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876944,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    },
    {
      "addr": 18446744071592369549,
      "name": "aspm_calc_l1ss_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:459",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070992,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
    },
    {
      "addr": 18446744071594231751,
      "name": "aspm_calc_l1ss_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256496,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:474",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:aspm_l1ss_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256496,
      "name": "aspm_calc_l1ss_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1500
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496983144,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230246640,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275650172,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584674023,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603175,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584673703,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
  "name": "aspm_calc_l1ss_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584781399,
      "name": "aspm_calc_l1ss_info",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:497",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state * link, struct aspm_register_info * upreg, struct aspm_register_info * dwreg)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 parent_l1ss_cap</code>
</li>
<li>
<b>Param added. </b>
<code>u32 child_l1ss_cap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aspm_register_info * upreg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aspm_register_info * dwreg</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void aspm_calc_l1ss_info(struct pcie_link_state * link, u32 parent_l1ss_cap, u32 child_l1ss_cap)
```
</details>
</li>
</ul>
