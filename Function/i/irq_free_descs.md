# Function: <code>irq_free_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579738192,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738192,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759936,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:461",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759936,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786368,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:649",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786368,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579783840,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:666",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783840,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579817216,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:659",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817216,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850960,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:676",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850960,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579897952,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:681",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897952,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932768,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932768,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982896,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982896,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580030768,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:742",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030768,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580014688,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:744",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014688,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015136,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:744",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015136,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147248,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:756",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147248,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580292096,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:733",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292096,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502368,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:760",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502368,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580574240,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:781",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574240,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580638480,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:781",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping_affinity_locked",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irq_dynamic",
        "drivers/xen/events/events_base.c:delayed_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638480,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491168680,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491168680,
      "name": "irq_free_descs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225195228,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_cleanup",
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225195228,
      "name": "irq_free_descs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284068080,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284068080,
      "name": "irq_free_descs",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271721466,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271721466,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951632,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951632,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889520,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irq_sim.c:irq_sim_fini",
        "kernel/irq/irq_sim.c:irq_sim_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889520,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943168,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943168,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void irq_free_descs(unsigned int from, unsigned int cnt)
```

```json
{
  "name": "irq_free_descs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990064,
      "name": "irq_free_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:736",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:devm_irq_desc_release",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "drivers/xen/events/events_base.c:xen_free_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990064,
      "name": "irq_free_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
