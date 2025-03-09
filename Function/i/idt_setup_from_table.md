# Function: <code>idt_setup_from_table</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033408,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:219",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033408,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579037632,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:220",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579037632,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042384,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:220",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042384,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050016,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050016,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052256,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052256,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609052812,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:196",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609052812,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612116306,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:172",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612116306,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614256620,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:172",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614256620,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615177545,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:180",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615177545,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616943364,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:188",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616943364,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627551600,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:188",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627551600,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619300912,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:188",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619300912,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621594400,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:191",
      "file": "arch/x86/kernel/idt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps",
        "arch/x86/kernel/idt.c:set_intr_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621594400,
      "name": "idt_setup_from_table.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052608,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052608,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578985376,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578985376,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052192,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052192,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```

```json
{
  "name": "idt_setup_from_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579056128,
      "name": "idt_setup_from_table",
      "external": false,
      "loc": "arch/x86/kernel/idt.c:218",
      "file": "arch/x86/kernel/idt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/idt.c:idt_setup_debugidt_traps",
        "arch/x86/kernel/idt.c:idt_setup_ist_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_pf",
        "arch/x86/kernel/idt.c:idt_setup_traps",
        "arch/x86/kernel/idt.c:idt_setup_early_traps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056128,
      "name": "idt_setup_from_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```
</details>
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
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
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void idt_setup_from_table(gate_desc * idt, const struct idt_data * t, int size, bool sys)
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
