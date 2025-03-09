# Function: <code>bind_evtchn_to_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858688,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858688,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189056,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189056,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370560,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:332",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370560,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452064,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:332",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452064,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862624,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:332",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862624,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093712,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:332",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093712,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204512,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:332",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204512,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585416864,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416864,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557584,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557584,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277088,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:347",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277088,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398144,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:505",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398144,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282112,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:522",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282112,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586796160,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:522",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586796160,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077488,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:522",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077488,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459472,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:523",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459472,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:524",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758992,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
    },
    {
      "addr": 18446744071596758173,
      "name": "bind_evtchn_to_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void bind_evtchn_to_cpu(struct irq_info * info, unsigned int cpu, bool force_affinity)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:513",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091616,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071597666621,
      "name": "bind_evtchn_to_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498219176,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498219176,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319296,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:337",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319296,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507984,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507984,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```

```json
{
  "name": "bind_evtchn_to_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616000,
      "name": "bind_evtchn_to_cpu",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:333",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616000,
      "name": "bind_evtchn_to_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>evtchn_port_t evtchn</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int chn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_affinity</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info * info</code>
</li>
<li>
<b>Param removed. </b>
<code>evtchn_port_t evtchn</code>
</li>
</ul>
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu)
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
