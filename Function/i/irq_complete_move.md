# Function: <code>irq_complete_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196160,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:652",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196160,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195223,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:654",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196784,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207383,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:654",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208464,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579203263,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:675",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206000,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579220607,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:912",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223664,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235978,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:928",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236048,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259642,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:919",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259712,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273691,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:916",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273760,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276107,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:927",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276176,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579298870,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:914",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304784,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304518,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:966",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310256,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579311910,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:999",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313072,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360582,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:999",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361936,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579418165,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:999",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425056,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501365,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:995",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508816,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513525,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:995",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521072,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542005,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:1053",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge",
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549888,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579274811,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:927",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274880,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579210155,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:927",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210224,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276011,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:927",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276080,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void irq_complete_move(struct irq_cfg * cfg)
```

```json
{
  "name": "irq_complete_move",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281899,
      "name": "irq_complete_move",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:927",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:apic_ack_edge"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281968,
      "name": "irq_complete_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void irq_complete_move(struct irq_cfg * cfg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void irq_complete_move(struct irq_cfg * cfg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void irq_complete_move(struct irq_cfg * cfg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void irq_complete_move(struct irq_cfg * cfg)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
