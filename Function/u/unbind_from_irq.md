# Function: <code>unbind_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861392,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1014",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861392,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191952,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1025",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191952,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373408,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1024",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373408,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454912,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1016",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454912,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865616,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1016",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865616,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096624,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1014",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096624,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207376,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1014",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207376,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585419776,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1015",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419776,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560480,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1015",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560480,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586281544,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1030",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586402136,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1379",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586284904,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1417",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586799608,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1423",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588081222,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1423",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589463254,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1425",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589763174,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1418",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590098688,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1415",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498222512,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1015",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498222512,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585322192,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1019",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322192,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510880,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1015",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510880,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618896,
      "name": "unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1015",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618896,
      "name": "unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void unbind_from_irq(unsigned int irq)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unbind_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void unbind_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void unbind_from_irq(unsigned int irq)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void unbind_from_irq(unsigned int irq)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
