# Function: <code>pci_msi_set_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583240356,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:153",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583385627,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:153",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583551167,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:163",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699725,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:163",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583687730,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:163",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837931,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:163",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583728338,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:161",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880195,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:161",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583986450,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:162",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584143683,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:162",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584180563,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:148",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360499,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:148",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584269203,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:157",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584455672,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:157",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584460110,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:162",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584652453,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:162",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584595422,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584788693,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585267791,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:188",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_msi_setup_pci_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480118,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:188",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585522198,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi.c:415",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585400214,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi.c:406",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585860594,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi.c:395",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_msi_set_enable(struct pci_dev * dev, int enable)
```

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587053976,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:241",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:pci_restore_msi_state"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052160,
      "name": "pci_msi_set_enable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_msi_set_enable(struct pci_dev * dev, int enable)
```

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588239652,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:270",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:msi_capability_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588235632,
      "name": "pci_msi_set_enable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_msi_set_enable(struct pci_dev * dev, int enable)
```

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588515156,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:270",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:msi_capability_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588511136,
      "name": "pci_msi_set_enable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_msi_set_enable(struct pci_dev * dev, int enable)
```

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588813748,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:271",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msi_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msi_state",
        "drivers/pci/msi/msi.c:msi_capability_init"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:msi_capability_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809728,
      "name": "pci_msi_set_enable",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496837548,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497055848,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230117892,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3230265588,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290911728,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291093444,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275543042,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275702354,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584547582,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737445,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584475742,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668213,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584545582,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738853,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msi_set_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584653326,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584846421,
      "name": "pci_msi_set_enable",
      "external": false,
      "loc": "drivers/pci/pci.h:187",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void pci_msi_set_enable(struct pci_dev * dev, int enable)
```
</details>
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
