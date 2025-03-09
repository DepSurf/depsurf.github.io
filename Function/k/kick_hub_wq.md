# Function: <code>kick_hub_wq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585157808,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:592",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157808,
      "name": "kick_hub_wq.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585559363,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:594",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550416,
      "name": "kick_hub_wq.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747043,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:597",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737584,
      "name": "kick_hub_wq.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585834247,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:606",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823184,
      "name": "kick_hub_wq.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586273645,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:606",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264928,
      "name": "kick_hub_wq.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586531150,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:609",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522240,
      "name": "kick_hub_wq.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586679739,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:610",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670848,
      "name": "kick_hub_wq.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586933327,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:642",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924384,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587131757,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587122832,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587973740,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:646",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969008,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588033484,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:646",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028768,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587914922,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:653",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910240,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588524838,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:653",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519680,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589932849,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:653",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927648,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void kick_hub_wq(struct usb_hub * hub)
```

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591509072,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:657",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591509072,
      "name": "kick_hub_wq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void kick_hub_wq(struct usb_hub * hub)
```

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591930464,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:657",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591930464,
      "name": "kick_hub_wq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void kick_hub_wq(struct usb_hub * hub)
```

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592670864,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:677",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592670864,
      "name": "kick_hub_wq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500207696,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500194032,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232687152,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232675420,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293494868,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_logical_disconnect",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293481424,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277131540,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277122294,
      "name": "kick_hub_wq.part.0",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586837837,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828912,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586779597,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770672,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587086317,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077392,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_hub_wq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587193469,
      "name": "kick_hub_wq",
      "external": false,
      "loc": "drivers/usb/core/hub.c:644",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:usb_wakeup_notification",
        "drivers/usb/core/hub.c:usb_kick_hub_wq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184544,
      "name": "kick_hub_wq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void kick_hub_wq(struct usb_hub * hub)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
