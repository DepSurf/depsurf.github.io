# Function: <code>io_apic_modify_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197120,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:436",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197120,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197712,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:436",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197712,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209408,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:435",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209408,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206928,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:435",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206928,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224608,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:436",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224608,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237008,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:437",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237008,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260672,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:437",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260672,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274784,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274784,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277216,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277216,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579308835,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:425",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:ioapic_ack_level",
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305920,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311585,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:417",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579314417,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:417",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363479,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:417",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579427263,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:418",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579511119,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:418",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579523567,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:419",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552111,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:419",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275920,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275920,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211248,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211248,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277120,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277120,
      "name": "io_apic_modify_irq",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```

```json
{
  "name": "io_apic_modify_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283008,
      "name": "io_apic_modify_irq",
      "external": false,
      "loc": "arch/x86/kernel/apic/io_apic.c:438",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:startup_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:unmask_ioapic_irq",
        "arch/x86/kernel/apic/io_apic.c:mask_ioapic_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283008,
      "name": "io_apic_modify_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void io_apic_modify_irq(struct mp_chip_data * data, int mask_and, int mask_or, void (*)(struct irq_pin_list *) final)
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
