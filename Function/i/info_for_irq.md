# Function: <code>info_for_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583856828,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858864,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584187180,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189264,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584368700,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:155",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370752,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450108,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:155",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452480,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860796,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:155",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863072,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585091884,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:155",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094160,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202716,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:155",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204960,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585414796,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417056,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585555516,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557776,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586275420,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:159",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278224,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586394300,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:255",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_ipis",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:restore_cpu_virqs",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586289864,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:265",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586805628,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:265",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588087787,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:265",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589470186,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:266",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589770113,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:267",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_get",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:evtchn_make_refcounted",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_needs_eoi_flag",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:pirq_check_eoi_map",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:cpu_from_evtchn"
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
  "name": "info_for_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590106192,
      "name": "info_for_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:251",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:lateeoi_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_pirq_from_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:startup_pirq",
        "drivers/xen/events/events_base.c:startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:irq_evtchn_from_virq",
        "drivers/xen/events/events_base.c:irq_evtchn_from_virq",
        "drivers/xen/events/events_base.c:evtchn_to_info",
        "drivers/xen/events/events_base.c:evtchn_to_info"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498216440,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498219368,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585317228,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:160",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319488,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585505916,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508176,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct irq_info * info_for_irq(unsigned int irq)
```

```json
{
  "name": "info_for_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585613900,
      "name": "info_for_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:156",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:rebind_evtchn_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:cpu_from_evtchn",
        "drivers/xen/events/events_base.c:evtchn_from_irq",
        "drivers/xen/events/events_base.c:xen_irq_info_virq_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_ipi_setup",
        "drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616192,
      "name": "info_for_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
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
struct irq_info * info_for_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irq_info * info_for_irq(unsigned int irq)
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
struct irq_info * info_for_irq(unsigned int irq)
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
