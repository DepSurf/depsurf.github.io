# Function: <code>pciehp_request</code>

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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584417968,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:127",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417968,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584614240,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:133",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614240,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584752176,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584752176,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585444588,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443584,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585593980,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585592976,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585472380,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471376,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585937725,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592381108,
      "name": "pciehp_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585937680,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587140538,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594244943,
      "name": "pciehp_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587140480,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343898,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596210343,
      "name": "pciehp_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588343840,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588619978,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596735495,
      "name": "pciehp_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588619920,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588920154,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:135",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597644079,
      "name": "pciehp_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588920096,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497015528,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497015528,
      "name": "pciehp_request",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275677252,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275675166,
      "name": "pciehp_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446743936275675212,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584700992,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700992,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584631760,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631760,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584702336,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702336,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
```

```json
{
  "name": "pciehp_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584809984,
      "name": "pciehp_request",
      "external": true,
      "loc": "drivers/pci/hotplug/pciehp_ctrl.c:137",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809984,
      "name": "pciehp_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void pciehp_request(struct controller * ctrl, int action)
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
void pciehp_request(struct controller * ctrl, int action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pciehp_request(struct controller * ctrl, int action)
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
