# Function: <code>pciehp_card_present</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584424137,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:374",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424000,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584620570,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:376",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620432,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758304,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758304,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585449472,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:436",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449472,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585597776,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:439",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597776,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476112,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:439",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476112,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585942400,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:439",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942400,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587145760,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:441",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145760,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588350464,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:441",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350464,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588626720,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:435",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626720,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588926896,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:436",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926896,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497022256,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497022256,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275680862,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275680862,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707120,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707120,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584637888,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637888,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584708464,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708464,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int pciehp_card_present(struct controller * ctrl)
```

```json
{
  "name": "pciehp_card_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816048,
      "name": "pciehp_card_present",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_hpc.c:400",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816048,
      "name": "pciehp_card_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool pciehp_card_present(struct controller * ctrl)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
int pciehp_card_present(struct controller * ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pciehp_card_present(struct controller * ctrl)
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
