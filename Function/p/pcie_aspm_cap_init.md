# Function: <code>pcie_aspm_cap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583333878,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:341",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583645578,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:341",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583783188,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:341",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583826396,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:479",
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
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584089435,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:504",
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
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584293201,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:529",
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
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584388492,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:527",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585712,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:542",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585712,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722160,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
    },
    {
      "addr": 18446744071584726408,
      "name": "pcie_aspm_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585374688,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585374688,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537648,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:543",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537648,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1019
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415712,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:543",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415712,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1019
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585877952,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:543",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877952,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072176,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:551",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072176,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588258528,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:623",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258528,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588534256,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:584",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588534256,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588829664,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:586",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588829664,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496981824,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496981824,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1900
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230245280,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230245280,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1900
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275648946,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275648946,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672640,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
    },
    {
      "addr": 18446744071584676888,
      "name": "pcie_aspm_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601792,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
    },
    {
      "addr": 18446744071584606040,
      "name": "pcie_aspm_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672320,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
    },
    {
      "addr": 18446744071584676568,
      "name": "pcie_aspm_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```

```json
{
  "name": "pcie_aspm_cap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcie_aspm_cap_init",
      "external": false,
      "loc": "drivers/pci/pcie/aspm.c:546",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780016,
      "name": "pcie_aspm_cap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1897
    },
    {
      "addr": 18446744071584784264,
      "name": "pcie_aspm_cap_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
```
</details>
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
void pcie_aspm_cap_init(struct pcie_link_state * link, int blacklist)
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
