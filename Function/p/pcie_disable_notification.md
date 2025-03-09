# Function: <code>pcie_disable_notification</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583373400,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:669",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583686760,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:673",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583825048,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:709",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583867912,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:717",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584131512,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:714",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl"
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
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584331011,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:698",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584422480,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:718",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422480,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584618896,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:720",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618896,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584756880,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756880,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448240,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:784",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448240,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585596544,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:787",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585596544,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585474752,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:823",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474752,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585941072,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:824",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585941072,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587144224,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:826",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144224,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588348688,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:828",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348688,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588624944,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:819",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624944,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588925120,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:820",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588925120,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497019856,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497019856,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275679456,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275679456,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584705696,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705696,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584636464,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636464,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584707040,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707040,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
```

```json
{
  "name": "pcie_disable_notification",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584814624,
      "name": "pcie_disable_notification",
      "external": false,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:734",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814624,
      "name": "pcie_disable_notification",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void pcie_disable_notification(struct controller * ctrl)
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
void pcie_disable_notification(struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_disable_notification(struct controller * ctrl)
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
