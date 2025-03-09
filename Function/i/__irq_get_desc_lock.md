# Function: <code>__irq_get_desc_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738928,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:538",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738928,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760688,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:599",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760688,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787536,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:787",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787536,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785056,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:804",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785056,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818528,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:793",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818528,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852384,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:810",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852384,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899376,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:815",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899376,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934192,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934192,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984320,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984320,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032624,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:876",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032624,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016368,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:827",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016368,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017040,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:827",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017040,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149264,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:839",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149264,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294064,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:816",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294064,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504960,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:843",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504960,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577104,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:862",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577104,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641392,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:862",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641392,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491171184,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491171184,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225196328,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225196328,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284070336,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:irq_set_parent",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284070336,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271722972,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271722972,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953056,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953056,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890928,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890928,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944592,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944592,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct irq_desc * __irq_get_desc_lock(unsigned int irq, long unsigned int * flags, bool bus, unsigned int check)
```

```json
{
  "name": "__irq_get_desc_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990944,
      "name": "__irq_get_desc_lock",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_irqchip_state",
        "kernel/irq/manage.c:irq_get_irqchip_state",
        "kernel/irq/manage.c:teardown_percpu_nmi",
        "kernel/irq/manage.c:prepare_percpu_nmi",
        "kernel/irq/manage.c:disable_percpu_irq",
        "kernel/irq/manage.c:irq_percpu_is_enabled",
        "kernel/irq/manage.c:enable_percpu_irq",
        "kernel/irq/manage.c:can_request_irq",
        "kernel/irq/manage.c:irq_set_irq_wake",
        "kernel/irq/manage.c:enable_irq",
        "kernel/irq/manage.c:__disable_irq_nosync",
        "kernel/irq/manage.c:irq_set_vcpu_affinity",
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/chip.c:irq_modify_status",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chip_data",
        "kernel/irq/chip.c:irq_set_msi_desc_off",
        "kernel/irq/chip.c:irq_set_handler_data",
        "kernel/irq/chip.c:irq_set_irq_type",
        "kernel/irq/chip.c:irq_set_chip",
        "kernel/irq/pm.c:rearm_wake_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990944,
      "name": "__irq_get_desc_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
